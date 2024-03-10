### 1. install extensions

copy and paste the following code block into a new file named `vs-extensions.txt`

```
ms-python.black-formatter
dsznajder.es7-react-js-snippets
miguelsolorio.fluent-icons
github.copilot
github.copilot-chat
ecmel.vscode-html-css
hsnazar.hyper-term-theme
johnpapa.vscode-peacock
esbenp.prettier-vscode
ms-python.vscode-pylance
ms-python.python
ms-python.debugpy
bradlc.vscode-tailwindcss
vue.volar
wakatime.vscode-wakatime
```

`cat vs-extensions.txt | xargs -L1 code --install-extension`

---

### 2. copy settings

```
{
  "workbench.colorTheme": "Hyper Term Black",
  "workbench.colorCustomizations": {
    "editorCursor.foreground": "#C839C5",
    "terminalCursor.foreground": "#C839C5"
  },
  "workbench.sideBar.location": "right",
  "workbench.tree.indent": 20,
  "workbench.productIconTheme": "fluent-icons",
  "window.openFilesInNewWindow": "on",
  "terminal.integrated.fontFamily": "MesloLGS NF",

  "editor.fontFamily": "Menlo, 'DejaVu Sans Mono', Consolas, 'Lucida Console', monospace",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.cursorStyle": "block",
  "editor.renderLineHighlight": "none",
  "editor.snippetSuggestions": "top",
  "editor.minimap.enabled": false,
  "editor.linkedEditing": true,
  "editor.formatOnSave": true,

  "wakatime.apiKey": "API_KEY",

  "[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter"
  },
  "[markdown]": {
    "files.trimTrailingWhitespace": false
  }
}
```
