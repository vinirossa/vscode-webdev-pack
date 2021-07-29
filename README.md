# WebDev Extension Pack

<!-- [![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/vscode-webdev-pack?color=success&label=Visual%20Studio%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=vscode-webdev-pack)  -->

A collection of essential extensions for web development based in React, NextJS, Styled Components and GraphQL created by [Webyx Co.](https://github.com/Webyx-Co)

## Included extensions
#### Development Tools
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [htmltagwrap](https://marketplace.visualstudio.com/items?itemName=bradgashler.htmltagwrap)
- [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
- [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.liveserver)
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
#### Language Support
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=visualstudioexptteam.vscodeintellicode)
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)
- [GraphQL](https://marketplace.visualstudio.com/items?itemName=graphql.vscode-graphql)
- [Apollo GraphQL](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo)
- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next)
- [Jest](https://marketplace.visualstudio.com/items?itemName=orta.vscode-jest)
- [Sass](https://marketplace.visualstudio.com/items?itemName=syler.sass-indented)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=editorconfig.editorconfig)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
#### Code Snippets
- [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.javascriptsnippets)
- [Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets](https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode)
- [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
- [Next.js snippets](https://marketplace.visualstudio.com/items?itemName=pulkitgangwar.nextjs-snippets)
- [Jest Snippet](https://marketplace.visualstudio.com/items?itemName=andys8.jest-snippets)
- [ExpressSnippet](https://marketplace.visualstudio.com/items?itemName=vladmrnv.expresssnippet)
- [EJS language support](https://marketplace.visualstudio.com/items?itemName=digitalbrainstem.javascript-ejs-support)

## Want to install only some extensions?
To install only some of the fonts, just edit the package.json file removing the unwanted extensionPack consequences and then follow the procedures below to install locally.

## How to develop and install locally
- Clone the repository
```bash
$ git clone https://github.com/Webyx-Co/vscode-webdev-pack
```
- Install vsce
```bash
$npm install -g vsce
```
- Create the extension package
```bash
$vsce package
```
- Install the extension via the .vsix file
1. Open VS Code
2. Select Extensions from the menu
3. Click More > Install from VSIX...
4. Select the reloaded-extension-pack-x.x.x.vsix file
5. Click Reload Now to reload the VS Code

## For more information

* [Webyx Co. Github](https://github.com/Webyx-Co)
