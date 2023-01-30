**Restart Unreal Editor - How to use the plugin:**
- If you downloaded the plugin from the [Unreal Marketplace](https://marketplace-website-node-launcher-prod.ol.epicgames.com/ue/marketplace/en-US/product/restart-editor-01) skip to the next step, if you downloaded it from [GitHub](https://github.com/Ares9323/Restart-Unreal-Engine-Editor-Plugin/releases) copy the "RestartEditor" folder inside "Engine/Plugins/Marketplace/"
- Enable the plugin in the Editor "Plugins" window
- Restart the editor
- You should have an icon in the top bar, click it or press CTRL+SHIFT+R to restart the editor.
- If you want to enable by default the extension for all your project, edit the "RestartEditor.uplugin" file that you can find in the folder: "Engine/Plugins/Marketplace/RestartEditor" and set "EnabledByDefault" to true, otherwise, you could use [this amazing tool to Disable and Enable plugins by default](https://github.com/DarknessFX/UEPlugins_DisableDefault).

**Advanced Restart Editor - How to use the plugin:**
- Download the plugin from the [Unreal Marketplace](https://unrealengine.com/marketplace/en-US/product/dbe5d2a00fa541b2917ae5c987ff5d62)
- Enable the plugin in the Editor "Plugins" window
- Restart the editor
- You should have an icon in the top bar, click it or press CTRL+ALT+R to restart the editor.
- Press CTRL+ALT+SHIFT+R to force restart the editor, no prompt to save file changes will show up.
- In Editor Settings you can change the behaviour of the extension from the Plugins tab section, select "Advanced Restart Editor Plugin"
![SettingsImage](https://github.com/Ares9323/Restart-Unreal-Engine-Editor-Plugin/blob/master/Pictures/Settings.png)
  - Look for Multiple Instances on Startup, if true the plugin will check if another instance of the editor is already running, if true it will ask you if you want to close it or continue opening it.
  - Allow Multiple Instances of same Project, if false the plugin will automatically close the other instance of the editor if you try to open the same project.
  - Show Notification on Auto Close, if true the plugin will show a notification when it closes the other instance of the editor.
  - Show Debug Dialogs, if true the plugin will show a debug dialog whenever a plugin action is performed.

- If you want to enable by default the extension for all your project, edit the "RestartEditor.uplugin" file that you can find in the folder: "Engine/Plugins/Marketplace/AdvancedRestartEditor" and set "EnabledByDefault" to true, otherwise, you could use [this amazing tool to Disable and Enable plugins by default](https://github.com/DarknessFX/UEPlugins_DisableDefault).



