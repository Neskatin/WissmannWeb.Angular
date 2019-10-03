# WissmannWeb Angular Essentials - Extension Pack for VS Code

[![Badge for version for Visual Studio Code extension Wissmann-Web.wissmannweb-angular](https://vsmarketplacebadge.apphb.com/version/Wissmann-Web.wissmannweb-angular.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-angular) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Wissmann-Web.wissmannweb-angular.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-angular) [![Rating](https://vsmarketplacebadge.apphb.com/rating-star/Wissmann-Web.wissmannweb-angular.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-angular) [![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?color=blue&style=flat-square)](http://opensource.org/licenses/MIT)

This extension pack for Visual Studio Code adds extensions that are amazingly useful for Angular development.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

> As tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

## Recommended Settings

Here are some of my recommended settings. These are optional, but I get asked a lot for them, so here they are.

### Editor settings

```json
  "workbench.colorTheme": "Default Light+",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",

  "editor.renderIndentGuides": false,
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": false,
  "editor.minimap.enabled": false,
  "editor.renderWhitespace": "none",
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "editor.wordWrap": "off",

  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
```

### Prettier settings

```json
  "prettier.singleQuote": true,
  "prettier.printWidth": 140,
```

### Todo Tree settings

```json
  "todo-tree.filtering.excludeGlobs": [
    "**/node_modules/**",
    "**/dist*/**"
  ],
  "todo-tree.tree.flat": true,
```

### TypeScript Hero settings

```json
  "typescriptHero.imports.organizeOnSave": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
```

### CSharp2TS settings

```json
  "csharp2ts.propertiesToCamelCase": true,
```

## Included

Here is the list of extensions the pack includes:

- [WissmannWeb.Editor](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-editor) - My prefered VS Code Editor extentions.
- [TypeScript Hero](https://marketplace.visualstudio.com/items?itemName=rbbit.typescript-hero) - Additional toolings for typescript
- [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin) - TSLint support for Visual Studio Code
- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) - Editor services for Angular templates
- [Angular 8 Snippets](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) - 242 Angular Snippets
- [CSharp2TS](https://marketplace.visualstudio.com/items?itemName=rafaelsalguero.csharp2ts) - Convert C# POCOs to typescript
