# Mes settings VS Code

## Font

- Fira Code

## Extensions

- French Language Pack for Visual Studio Code
- Laravel Blade Snippets
- Material Icon Theme
- PHP DocBlocker
- PHP Intelephense
- Prettier - Code formatter
- Pylance
- Python
- Rainbow CSV
- Vetur

## Thème

- Tokyo Night

## Settings (JSON)

```json
{
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.shell.windows": "C:\\windows\\system32\\cmd.exe",
  "terminal.integrated.shellArgs.windows": ".",
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features",
    "editor.formatOnSave": true
  },
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded", //compressed  //expanded
      "extensionName": ".css",
      "savePath": "/css"
    }
  ],
  "workbench.startupEditor": "newUntitledFile",
  "liveSassCompile.settings.autoprefix": [],
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": null,
  "workbench.iconTheme": "material-icon-theme",
  "[php]": {
    "editor.tabSize": 4,
    "editor.defaultFormatter": "bmewburn.vscode-intelephense-client",
    "editor.formatOnSave": true
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 4,
    "editor.formatOnSave": true
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 4,
    "editor.formatOnSave": true
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "php-cs-fixer.rules": "@PhpCsFixer",
  "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
  "editor.fontWeight": null,
  "workbench.colorTheme": "Tokyo Night Storm",
  "blade.format.enable": true,
  "beautify.language": {
    "html": ["blade", "html"]
  },
  "eslint.validate": ["javascript", "vue"],
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "launch": {
    "configurations": [],
    "compounds": []
  },
  "workbench.colorCustomizations": {
    "statusBar.background": "#2f424b",
    "statusBar.foreground": "#79a3b6",
    "statusBar.noFolderBackground": "#333",
    "statusBar.noFolderForeground": "#fff"
  },
  "workbench.tree.indent": 14,
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter-notebook"
  },
  "notebook.cellToolbarLocation": {
    "default": "right",
    "jupyter-notebook": "left"
  },
  "editor.tabSize": 2,
  "editor.detectIndentation": false,
  "editor.foldingMaximumRegions": 8000,
  "php.validate.executablePath": "C:\\laragon\\bin\\php\\php-7.4.13-Win32-vc15-x64\\php.exe",
  "editor.formatOnSave": true,
  "eslint.format.enable": true,
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "explorer.compactFolders": false,
  "explorer.autoReveal": false
}
```
