Configuration for VS code prettier configuration

Install VS code pluggin and enable

1. Install this plugin Prettier - Code formatter
2. Enable it


Change the editor settings configuration

1. Use CMD + p / Ctrl + p to open editor settings.
2. Toggle to json view.
3. Add the below configuration to the settings.json file

    ```js
    {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
        "editor.formatOnSave": true
    }
    ```