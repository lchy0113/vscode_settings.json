# How to set up a Visual Studio code workspace
> Project to manage vscode settings
Visual Studio code can be set in a file written in JSON format called settings.json.

## About Sttings.json
If you select "File (F)" menu-> "Basic settings (P)"-> "Settings (S)" of VS Code, the default setting list will be displayed on the left side and Settings.json will be displayed on the right side. If you want to change the settings, edit the Settings.json file, save and apply.

## Settings.json storage location
The storage locatio differs depending on your environment.
- Windows% APPDATA% \ Code \ User \ settings.json
- Mac $ HOME / Library / Application Support / Code / User / settings.json
- Linux $ HOME / .config / Code / User / settings.json

## About the Settings.json file stored here
The setting contents and description method that can be defined in Setting.json may differ depending on the version of VSCode. Please refer to it when you want to review the past default settings or when you want to see what settings can be made.
1. Start Setting.json
2. Copy and paste the item you want to set from the default setting list
* For example, if you want to increase the font size, copy and paste "editor.fontSize": 18. Don't forget {} (brace / curly braces) at this time.

```json
{
"editor.fontSize": 18
}
```
3. save



## Reference
[Visual Studio Code User and Workspace Settings](https://code.visualstudio.com/docs/getstarted/settings)