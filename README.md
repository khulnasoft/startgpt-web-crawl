# Start-GPT-Plugin-Template
A starting point for developing your own external plug-in for Start-GPT

### Notes for plugin developers

- If you want your plugin to live within the codebase, fork the [plugins repo](https://github.com/KhulnaSoft/Start-GPT-Plugins) instead. Read the notes there
- For a more thorough and current guide, please refer to the [plugins repository](https://github.com/KhulnaSoft/Start-GPT-Plugins).
- If you use this repo for your own plugin, **EDIT This README**

### How to use a plugin

1. **Clone the plugin repo** into the Start-GPT's plugins folder
2. **Install the plugin's dependencies (if any):**
   Navigate to the plugin's folder in your terminal, and run the following command to install any required dependencies:

   ``` shell
      pip install -r requirements.txt
   ```
4. Update your plugins_config.yaml file to enable the plugin. If you skip this step the plugin won't be loaded

   ```shell
   plugin_folder:
      - config: {} # Configs from the plugin README and installation instructions.
      - enabled: true
   ```
