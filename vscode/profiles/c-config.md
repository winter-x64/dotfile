# C / C++ Profile for vscode

```json
{
  "tabnine.experimentalAutoImports": true,
  "editor.fontFamily": "'JetBrainsMono Nerd Font', Consolas, 'Courier New', monospace ",
  "editor.fontLigatures": true,
  "editor.fontSize": 12,
  "editor.fontWeight": 500,
  "editor.formatOnType": true,
  "editor.lineHeight": 2.5,
  "editor.letterSpacing": 0.5,
  "editor.guides.bracketPairs": "active",
  "window.titleSeparator": " | ",
  "window.title": "${appName}${separator}${rootName}${separator}${dirty}${activeEditorShort}",
  "editor.cursorBlinking": "expand",
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 4,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "workbench.startupEditor": "none",
  "editor.linkedEditing": true,
  "editor.minimap.renderCharacters": false,
  "codesnap.transparentBackground": true,
  "codesnap.boxShadow": "rgba(0, 0, 0, 0) 0px 20px 68px",
  "diffEditor.wordWrap": "off",
  "editor.wordWrap": "on",
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "entity.name.type.class",
          "keyword",
          "constant",
          "storage.modifier",
          "variable.parameter",
          "string.quoted"
        ],
        "settings": {
          "fontStyle": "italic "
        }
      },
      {
        "scope": [
          "variable.name",
          "constant.numeric",
          "string.quoted.triple",
          "keyword.control",
          "storage",
          "meta.tag"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "scope": [
          // Test Variable
          "entity.name.function",
          "comment"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  },
  "editor.accessibilitySupport": "off",
  "editor.stickyScroll.enabled": true,
  "indentRainbow.colors": [
    "rgba(16,16,16,0.1)",
    "rgba(16,16,16,0.3)",
    "rgba(16,16,16,0.6)",
    "rgba(16,16,16,0.4)",
    "rgba(16,16,16,0.2)"
  ],
  "indentRainbow.errorColor": "rgb(247, 132, 81, 0.6)",
  "indentRainbow.tabmixColor": "rgba(128,32,96,0.6)",
  "indentRainbow.colorOnWhiteSpaceOnly": true,
  "git.autofetch": true,
  "git.confirmSync": false,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "terminal.integrated.fontSize": 12,
  "search.actionsPosition": "auto",
  "search.experimental.notebookSearch": true,
  "git.mergeEditor": true,
  "git.postCommitCommand": "sync",
  "markdown.validate.enabled": true,
  "markdown.updateLinksOnFileMove.enabled": "always",
  "window.menuBarVisibility": "toggle",
  "explorer.autoRevealExclude": {
    "/env": true,
    "/venv": true,
    "/.venv": true
  },
  "problems.defaultViewMode": "table",
  "workbench.editorAssociations": {
    "*.db": "default"
  },
  "projectManager.git.baseFolders": ["d:\\CodinWays\\"],
  "projectManager.tags": ["Personal", "Work", "My Course"],
  "editor.minimap.scale": 1,
  "editor.minimap.autohide": true,
  "symbols.hidesExplorerArrows": false,
  "workbench.iconTheme": "simple-icons",
  "workbench.colorTheme": "Community Material Theme Darker High Contrast", // false is the default
  "terminal.integrated.enableImages": true,
  "terminal.integrated.copyOnSelection": true,
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorWidth": 5,
  "terminal.integrated.shellIntegration.suggestEnabled": true,
  "terminal.integrated.tabs.title": "${process}${separator}${task}",
  "liveshare.sharedTerminalHeight": 100,
  "liveshare.sharedTerminalWidth": 170,
  "workbench.commandPalette.experimental.suggestCommands": true,
  "editor.tabCompletion": "on",
  "code-runner.clearPreviousOutput": true,
  "code-runner.runInTerminal": true,
  "code-runner.saveFileBeforeRun": true,
  "workbench.sideBar.location": "right",
  "window.commandCenter": false,
  "workbench.productIconTheme": "el-vsc-v1-icons",
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 3000
}
```
