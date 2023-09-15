# VS Code Settings

List of All Extensions Themes and Settings that I like to use with **VC Code**.

## Default for all profile

- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [CodeSnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)
- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [vscode-pdf](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [FontSize Shortcuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts) -- optional
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Pieces for VS Code](https://marketplace.visualstudio.com/items?itemName=MeshIntelligentTechnologiesInc.pieces-vscode)
- [todo tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [code spell checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

## Extension Language Specific

- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

## C/C++**

- [C/C++ Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)
- [Better C++ Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax)
- [C/C++ Advanced Lint](https://marketplace.visualstudio.com/items?itemName=jbenden.c-cpp-flylint)
- [C/C++ Project Generator](https://marketplace.visualstudio.com/items?itemName=danielpinto8zz6.c-cpp-project-generator)
- [C/C++ Snippets](https://marketplace.visualstudio.com/items?itemName=hars.CppSnippets)

## Java

- [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

## HTML CSS JS

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
- [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
- [CSS Var Complete](https://marketplace.visualstudio.com/items?itemName=phoenisx.cssvar)
- [className Completion in CSS](https://marketplace.visualstudio.com/items?itemName=zitup.classnametocss)
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
- [Color Info](https://marketplace.visualstudio.com/items?itemName=bierner.color-info)
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next)
- [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
- [postman](https://marketplace.visualstudio.com/items?itemName=Postman.postman-for-vscode)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Babel js](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)

## Node js - npm, yarn etc

- [NPM](https://marketplace.visualstudio.com/items?itemName=idered.npm)
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- [npm Outdated](https://marketplace.visualstudio.com/items?itemName=mskelton.npm-outdated)

## React

- [React CSS modules](https://marketplace.visualstudio.com/items?itemName=viijay-kr.react-ts-css)

## Theme and icons

- [Tokyo Night](https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night)

- [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl)

- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

- [Just Black](https://marketplace.visualstudio.com/items?itemName=nur.just-black)

## Fonts

- [Cascadia Mono PL](https://github.com/microsoft/cascadia-code)
- [Operator Mono](https://www.typography.com/fonts/operator/styles) (if want italic feels)
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
- [Anonymous Pro](https://fonts.google.com/specimen/Anonymous+Pro)
- [PT Mono](#)

## Extras

- [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)

## Settings (User Settings - JSON)

```JSON
{
  //Search Prefs
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/*.code-search": true
  },
  "search.useIgnoreFiles": false,

  //Workbench Prefs
  "workbench.sideBar.location": "right",
  "workbench.iconTheme": "vscode-icons",
  "workbench.colorTheme": "Tokyo Night",
  "workbench.editorLargeFileConfirmation": 2048,
  //for theme night-owl - Separate the Editor from the Sidebar only
  /*  "workbench.colorCustomizations": {
    "[Night Owl]": {
      "activityBar.background": "#000C1D",
      "activityBar.border": "#102a44",
      "editorGroup.border": "#102a44",
      "sideBar.background": "#001122",
      "sideBar.border": "#102a44",
      "sideBar.foreground": "#8BADC1"
    },
    "[Night Owl (No Italics)]": {
      "activityBar.background": "#000C1D",
      "activityBar.border": "#102a44",
      "editorGroup.border": "#102a44",
      "sideBar.background": "#001122",
      "sideBar.border": "#102a44",
      "sideBar.foreground": "#8badc1"
    }
  }, */

  "explorer.openEditors.visible": 0,
  "explorer.confirmDelete": false,
  "editor.suggestSelection": "first",
  "editor.snippetSuggestions": "top",
  "editor.linkedEditing": true, //Automatically edit a closing tag when editing an opening tag
  "editor.formatOnPaste": false,
  "editor.emptySelectionClipboard": false,
  "editor.formatOnSave": true,
  "editor.minimap.enabled": false,
  "editor.fontFamily": "'Cascadia Mono PL','Operator Mono','JetBrains Mono'",
  "editor.fontSize": 16,
  "editor.indentSize": "tabSize",
  "editor.tabSize": 2,
  "editor.detectIndentation": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.scrollBeyondLastLine": false,
  "editor.wordWrap": "on",

  "editor.lineHeight": 1.8,
  

  //terminal prefs
  "terminal.integrated.fontFamily": "'Anonymous Pro'",
  "terminal.integrated.fontWeight": "bold",
  "terminal.integrated.fontSize": 18,

  "git.autofetch": true,
  "diffEditor.ignoreTrimWhitespace": false, //for git tarce

  "vsicons.dontShowNewVersionMessage": true,
  "extensions.ignoreRecommendations": true,
  "terminal.external.osxExec": "iterm.app",
  "terminal.explorerKind": "external",
  "editor.mouseWheelZoom": false,

  //rest custome prefs goes here time to time
  
  "javascript.updateImportsOnFileMove.enabled": "always",

  "window.restoreWindows": "preserve",
  "cph.general.defaultLanguage": "java",
  "eslint.enable": true,
  "eslint.validate": ["vue", "react", "typescript", "javascript"],

  "prettier.tabWidth": 2,

  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "[python]": {
    "editor.formatOnType": true
  }
}
```

## Keybindings

```JSON
[
  {
    "key": "cmd+1",
    "command": "workbench.action.openEditorAtIndex1"
  },
  {
    "key": "ctrl+1",
    "command": "-workbench.action.openEditorAtIndex1"
  },
  {
    "key": "cmd+2",
    "command": "workbench.action.openEditorAtIndex2"
  },
  {
    "key": "ctrl+2",
    "command": "-workbench.action.openEditorAtIndex2"
  },
  {
    "key": "cmd+3",
    "command": "workbench.action.openEditorAtIndex3"
  },
  {
    "key": "ctrl+3",
    "command": "-workbench.action.openEditorAtIndex3"
  },
  {
    "key": "cmd+4",
    "command": "workbench.action.openEditorAtIndex4"
  },
  {
    "key": "ctrl+4",
    "command": "-workbench.action.openEditorAtIndex4"
  },
  {
    "key": "cmd+5",
    "command": "workbench.action.openEditorAtIndex5"
  },
  {
    "key": "ctrl+5",
    "command": "-workbench.action.openEditorAtIndex5"
  },
  {
    "key": "cmd+6",
    "command": "workbench.action.openEditorAtIndex6"
  },
  {
    "key": "ctrl+6",
    "command": "-workbench.action.openEditorAtIndex6"
  },
  {
    "key": "cmd+7",
    "command": "workbench.action.openEditorAtIndex7"
  },
  {
    "key": "ctrl+7",
    "command": "-workbench.action.openEditorAtIndex7"
  },
  {
    "key": "cmd+8",
    "command": "workbench.action.openEditorAtIndex8"
  },
  {
    "key": "ctrl+8",
    "command": "-workbench.action.openEditorAtIndex8"
  },
  {
    "key": "cmd+9",
    "command": "workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+9",
    "command": "-workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+1",
    "command": "workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "cmd+1",
    "command": "-workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "ctrl+3",
    "command": "workbench.action.focusThirdEditorGroup"
  },
  {
    "key": "cmd+3",
    "command": "-workbench.action.focusThirdEditorGroup"
  },
  {
    "key": "ctrl+6",
    "command": "workbench.action.focusSixthEditorGroup"
  },
  {
    "key": "cmd+6",
    "command": "-workbench.action.focusSixthEditorGroup"
  },
  {
    "key": "ctrl+7",
    "command": "workbench.action.focusSeventhEditorGroup"
  },
  {
    "key": "cmd+7",
    "command": "-workbench.action.focusSeventhEditorGroup"
  },
  {
    "key": "ctrl+2",
    "command": "workbench.action.focusSecondEditorGroup"
  },
  {
    "key": "cmd+2",
    "command": "-workbench.action.focusSecondEditorGroup"
  },
  {
    "key": "ctrl+4",
    "command": "workbench.action.focusFourthEditorGroup"
  },
  {
    "key": "cmd+4",
    "command": "-workbench.action.focusFourthEditorGroup"
  },
  {
    "key": "ctrl+5",
    "command": "workbench.action.focusFifthEditorGroup"
  },
  {
    "key": "cmd+5",
    "command": "-workbench.action.focusFifthEditorGroup"
  },
  {
    "key": "ctrl+8",
    "command": "workbench.action.focusEighthEditorGroup"
  },
  {
    "key": "cmd+8",
    "command": "-workbench.action.focusEighthEditorGroup"
  }
]
```
