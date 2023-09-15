# VS Code Settings

- [VS Code Settings](#vs-code-settings)
  - [Extension list](#extension-list)
    - [Default for all profile](#default-for-all-profile)
    - [C/C++\*\*](#cc)
    - [Java](#java)
    - [HTML CSS JS](#html-css-js)
    - [Node js - npm, yarn etc](#node-js---npm-yarn-etc)
    - [React](#react)
  - [Theme and icons](#theme-and-icons)
  - [Fonts](#fonts)
  - [Extras](#extras)
  - [Settings (User Settings - JSON)](#settings-user-settings---json)
  - [Keybindings](#keybindings)

## Extension list

### Default for all profile

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
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

### C/C++**

- [C/C++ Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)
- [Better C++ Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax)
- [C/C++ Advanced Lint](https://marketplace.visualstudio.com/items?itemName=jbenden.c-cpp-flylint)
- [C/C++ Project Generator](https://marketplace.visualstudio.com/items?itemName=danielpinto8zz6.c-cpp-project-generator)
- [C/C++ Snippets](https://marketplace.visualstudio.com/items?itemName=hars.CppSnippets)

### Java

- [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

### HTML CSS JS

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

### Node js - npm, yarn etc

- [NPM](https://marketplace.visualstudio.com/items?itemName=idered.npm)
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- [npm Outdated](https://marketplace.visualstudio.com/items?itemName=mskelton.npm-outdated)

### React

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
  /* zoom size of vscode window */
  "window.zoomLevel": -1,
  /* search */
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/*.code-search": true
  },
  "search.useIgnoreFiles": false,
  "extensions.ignoreRecommendations": true,
  /* auto save */
  "files.autoSave": "afterDelay",
  "files.exclude": {
    "**/.*": true
  },
  /* workbench, sidebar,etc */
  "workbench.colorTheme": "Bearded Theme Black & Diamond",
  "workbench.sideBar.location": "right",
  "workbench.tree.indent": 15,
  "workbench.tree.renderIndentGuides": "always",
  "workbench.colorCustomizations": {
    "tree.indentGuidesStroke": "#05ef3c"
  },
  "vsicons.dontShowNewVersionMessage": false,
  "workbench.iconTheme": "vscode-icons",
  /* explorer setting */
  //  "explorer.openEditors.visible": 1,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.compactFolders": false,
  /* editor setting */
  "editor.snippetSuggestions": "top",
  "editor.linkedEditing": true,
  "editor.formatOnPaste": false,
  "editor.emptySelectionClipboard": false,
  "editor.formatOnSave": true,
  "editor.fontFamily": "'PT Mono','Cascadia Mono PL','JetBrains Mono','Operator Mono'",
  "editor.fontWeight": "300",
  "editor.letterSpacing": 1.5,
  "editor.cursorBlinking": "expand",
  "editor.indentSize": "tabSize",
  "editor.detectIndentation": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.mouseWheelZoom": false,
  "editor.inlineSuggest.enabled": true,
  "editor.wordWrap": "on",
  "editor.tabSize": 2,
  "editor.insertSpaces": false,
  "editor.wrappingIndent": "indent",
  "editor.suggestSelection": "first",
  "editor.lineHeight": 0,
  "editor.fontSize": 18,
  "editor.guides.bracketPairs": true,
  "editor.minimap.autohide": true,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.scale": 2,
  "editor.renderWhitespace": "boundary",
  "editor.tokenColorCustomizations": {
    "comments": "#8c9639"
  },
  //"editor.scrollBeyondLastLine": false,
  //"editor.formatOnPaste": false,
  /* terminal */
  "terminal.integrated.fontFamily": "'PT Mono','CaskaydiaCove Nerd Font Mono', 'Anonymous Pro'",
  "terminal.integrated.fontWeight": "normal",
  "terminal.integrated.fontSize": 18,

  "terminal.external.osxExec": "iterm.app",
  "terminal.explorerKind": "external",
  "terminal.integrated.hideOnStartup": "always",
  "terminal.integrated.env.osx": {},

  "pieces.setCopilotLocation": true,

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
  "[python]": {
    "editor.formatOnType": true
  },
  "redhat.telemetry.enabled": false,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "eslint.enable": true,
  "eslint.validate": ["vue", "react", "typescript", "javascript"],
  "prettier.jsxSingleQuote": true,
  "prettier.bracketSameLine": true,
  "prettier.bracketSpacing": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "liveServer.settings.donotVerifyTags": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "[markdown]": {
    "editor.defaultFormatter": "DavidAnson.vscode-markdownlint"
  },
  "git.openRepositoryInParentFolders": "always", //github
  "diffEditor.experimental.showMoves": true,
  "git.autofetch": true,
  "diffEditor.ignoreTrimWhitespace": false, //for git tarce
  "cSpell.userWords": ["Codepen", "concat", "iostream"],
  "todo-tree.general.tags": [
    "BUG",
    "HACK",
    "FIXME",
    "TODO",
    "XXX",
    "[ ]",
    "[x]",
    "DOUBT"
  ],
  "code-runner.runInTerminal": true
}
//"jsxBracketSameLine": false,
//"jsxSingleQuote": false,
//  "singleQuote": false,
//arrowParens": "always",
//"bracketSpacing": true,

```

## Keybindings

```JSON
// Place your key bindings in this file to override the defaults
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
  },
  {
    "key": "shift+cmd+v",
    "command": "-markdown.extension.closePreview",
    "when": "markdownPreviewFocus"
  },
  {
    "key": "cmd+k v",
    "command": "-markdown.extension.closePreview",
    "when": "markdownPreviewFocus"
  },
  {
    "key": "shift+cmd+v",
    "command": "-markdown.showPreview",
    "when": "!notebookEditorFocused && editorLangId == 'markdown'"
  },
  {
    "key": "alt+p",
    "command": "workbench.profiles.actions.switchProfile"
  }
]
```
