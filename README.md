# PROJECT BurgerBuilder

## Description
```
Data from Firebase
‘Axios’ and 'XMLHTTPREQUEST' are used to get the data and fill the state in the stateful component.

- This is a customized burger builder application. 
- User must log in or create an account to order.
- After signing in the user creats his own burger layers from salad, bacon, cheese and meat, the ingredients and its' prices shows real-time while adding the burger layers.
- The user then enters his/her information from name, address, country, zip and e-mail and chooses a fast delivery or a normal one.
- The user can view the history of his/her orders. 

Hints:
o Desktop and Mobile App.

```


## Requirements

For development, you will only need Node.js installed on your environement.

### Node

[Node](http://nodejs.org/) is really easy to install & now include [NPM](https://npmjs.org/).
You should be able to run the following command after the installation procedure
below.

    $ node --version
    v0.10.24

    $ npm --version
    1.3.21

#### Node installation on OS X

You will need to use a Terminal. On OS X, you can find the default terminal in
`/Applications/Utilities/Terminal.app`.

Please install [Homebrew](http://brew.sh/) if it's not already done with the following command.

    $ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

If everything when fine, you should run

    brew install node

#### Node installation on Linux

    sudo apt-get install python-software-properties
    sudo add-apt-repository ppa:chris-lea/node.js
    sudo apt-get update
    sudo apt-get install nodejs

#### Node installation on Windows

Just go on [official Node.js website](http://nodejs.org/) & grab the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it.

---

## Install

    $ git clone https://github.com/amrshaawkyy/BurgerBuilder
    $ cd PROJECT
    $ npm install

## Start & watch

    $ npm start

## Simple build for production

    $ npm run build

## Update sources

Some packages usages might change so you should run `npm prune` & `npm install` often.
A common way to update is by doing

    $ git pull
    $ npm prune
    $ npm install

To run those 3 commands you can just do

    $ npm run pull

## Enable git hooks (unix only :/)

    $ npm run create-hook-symlinks

### `post-merge` (≃ `npm install`)

This hook will `npm prune && npm install` each time you `git pull` something if the `package.json` has been modified.

### `pre-commit` (≃ `npm test`)

This hook will just ensure you will commit something not broken bye pruning npm packages not in the `package.json` & eventually reinstall missings/not correctly removed packages.
Then it will try a production build.

---

## Languages & tools

### HTML

### CSS
- [styled-components](https://styled-components.com/).

### JavaScript

- [React](http://facebook.github.io/react).
- [Redux](https://redux.js.org/).
- [Webpack](https://webpack.js.org/).
- [Babel](https://babeljs.io/).

### Axios
