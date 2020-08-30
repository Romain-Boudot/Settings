# Settings

## VSCode

### Config JSON

```
{
    "window.zoomLevel": 0,
    "editor.letterSpacing": 1,
    "editor.lineHeight": 25,
    "eslint.alwaysShowStatus": true,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "workbench.colorTheme": "Community Material Theme Darker",
    "window.restoreWindows": "all",
    "workbench.tree.indent": 10,
    "editor.minimap.renderCharacters": false,
    "python.jediEnabled": false,
    "editor.tabSize": 2,
    "git.confirmSync": false,
    "liveServer.settings.donotShowInfoMsg": true,
    "python.languageServer": "Microsoft",
    "eslint.format.enable": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
        "source.fixAll.tslint": true
    },
    
    // "editor.occurrencesHighlight": false, // removes highlights occurrences (still works when you select a word)
    // "editor.glyphMargin": false, // removes the space used mainly for debugging indicators
    // "explorer.openEditors.visible": 0, // removes the open editors section at the top of the sidebar, you can see the opened files with ⌘ + ⌥ + Tab
    // "workbench.editor.showIcons": false, // removes icon from opened files in tabs
    "editor.fontLigatures": true,
    "editor.minimap.enabled": false, // removes minimap
    "editor.renderWhitespace": "none", // removes whitespace chars
    "editor.renderIndentGuides": false, // removes indent guides
    "editor.renderLineHighlight": "none", // removes line highlight
    "editor.overviewRulerBorder": false, // removes border from overview ruler (located on the right, same position as the scrollbar)
    "editor.hideCursorInOverviewRuler": true, // hides cursor mark in the overview ruler
    "editor.folding": false, // removes the folding feature
    "editor.matchBrackets": "never", // removes the highlight of matching brackets (I use Subtle Match Brackets extension for this)
    "workbench.activityBar.visible": false, // removes the activity bar (the 4 icons at the left of the screen), so now you will have to open the explorer, git, debugger and extension with shortcuts or through the Command Palette
    "workbench.editor.tabCloseButton": "off", // removes cross icon from tabs
    "workbench.statusBar.visible": false, // removes the status bar
    "indenticator.color.dark": "rgba(255,255,255,.1)", // adds a subtle indent guide (needs Indenticator extension)
    "workbench.colorCustomizations": { // object that allows you to customize your color theme: https://code.visualstudio.com/docs/getstarted/theme-color-reference 
        "tab.activeBorder": "#0000" // removes border to highlight active tabs (the colors formats are: #RGB, #RGBA, #RRGGBB or #RRGGBBAA)
    },
}
```

### extensions

- amlovey.shaderlabvscodefree
- boundarystudio.csharp-extentions-pack
- cemuka.unity-code-snippets
- CoenraadS.bracket-pair-colorizer
- dbaeumer.vscode-eslint
- eamodio.gitlens
- eg2.tslint
- eppz.eppz-code
- Equinusocio.vsc-community-material-theme
- Equinusocio.vsc-material-theme
- equinusocio.vsc-material-theme-icons
- formulahendry.code-runner
- HookyQR.beautify
- jchannon.csharpextensions
- johnpapa.Angular2
- jorgeserrano.vscode-csharp-snippets
- kleber-swf.unity-code-snippets
- liximomo.sftp
- mp.vscode-oracle-format
- ms-dotnettools.csharp
- ms-python.python
- ms-vscode.vscode-typescript-tslint-plugin
- ms-vsliveshare.vsliveshare
- mycelo.oracle-plsql
- octref.vetur
- ritwickdey.LiveServer
- shd101wyy.markdown-preview-enhanced
- slevesque.shader
- sumneko.lua
- tht13.python
- Tobiah.unity-tools
- Unity.unity-debug
- vscode-snippet.snippet
- YclepticStudios.unity-snippets
