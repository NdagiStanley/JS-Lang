# JS - JavaScript

JS programming Language

## Installation

```bash
brew install nodejs
```

Or the recommended way from NodeJS' website:

```bash
curl "https://nodejs.org/dist/latest/node-${VERSION:-$(wget -qO- https://nodejs.org/dist/latest/ | sed -nE 's|.*>node-(.*)\.pkg</a>.*|\1|p')}.pkg" > "$HOME/Downloads/node-latest.pkg" && sudo installer -store -pkg "$HOME/Downloads/node-latest.pkg" -target "/"
```

### Versions

Recommended: [nvm](https://github.com/nvm-sh/nvm#intro)

Have (the `NVM` portion of my [.zshrc](https://github.com/NdagiStanley/dotfiles/blob/main/.zshrc)):

```sh
...
## NVM
export NVM_DIR="$HOME/.nvm"
...
```

in your `.zshrc` or `.bashrc` (or equivalent) then install `nvm`: (brew install [is not recommended](https://github.com/nvm-sh/nvm#important-notes)!)

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```

Common commands:

```bash
nvm list
nvm install --lts
nvm install 16
nvm use node
nvm use 16
```

Further: use [.nvmrc](https://github.com/nvm-sh/nvm#nvmrc), including [shell integration](https://github.com/nvm-sh/nvm#deeper-shell-integration).

## Implementation

Run:

```bash
node index.js
```

## More

**Node.js** is a JavaScript runtime built on Chrome's V8 JavaScript engine.

---
Ref:
- [JS on w3schools.com](https://www.w3schools.com/js/default.asp)
- [JS on GeeksforGeeks.com](https://www.geeksforgeeks.org/javascript-tutorial/)
- [JS glossary on codecademy.com](https://www.codecademy.com/articles/glossary-javascript)
- [Node.js on w3schools.com](https://www.w3schools.com/nodejs/default.asp)
