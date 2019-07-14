# 3YOURMIND Frontend Recommended pack

This pack is geared towards frontend Vue project development.

## Included Extensions

- [Alphabetical Sorter](https://marketplace.visualstudio.com/items?itemName=ue.alphabetical-sorter)
- [Auto Complete Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag)
- [Babel Javascript](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [CodeMetrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics)
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
- [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Hightlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
- [Indenticator](https://marketplace.visualstudio.com/items?itemName=SirTori.indenticator)
- [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [LintLens](https://marketplace.visualstudio.com/items?itemName=ghmcadams.lintlens)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Regex Previewer](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)
- [Shell Format](https://marketplace.visualstudio.com/search?term=shell%20format&target=VSCode&category=All%20categories&sortBy=Relevance)
- [Stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)
- [Table Formatter](https://marketplace.visualstudio.com/items?itemName=shuworks.vscode-table-formatter)
- [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [Vue Peek](https://marketplace.visualstudio.com/items?itemName=dariofuzinato.vue-peek)
- [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

## Installation

- clone the pack's repository.
- [optional] you can clear all preexisting vscode extensions by deleting all the files in your `~/.vscode/extensions` folder (linux/mac) or `%USER%\\.vscode\extensions` (windows).
- install the .vsix file by executing `code --install-extension 3yourmind-frontend-recommended-0.0.1.vsix` in your terminal (in the root folder of the cloned repository).

## To contribute

- install the [Visual Studio Core Extension](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) globally by executing `npm install -g vsce` in your terminal.
- create a branch for your changes.
- make your changes to the `extensionPack` section of `package.json`.
- update `README.md` (and if necessary also `CHANGELOG.md`) accordingly.
- in the root folder of the repo run `vsce package`.
- submit a pull request with your changes and include a description.
