# **NPM** or the _Node Package Manager_, is one of the most used tools for any Node.js developer.

## Install package.json dependencies<br>

- **_npm install_**

## Shorthand

<br>

## install

- **_npm i `<package>`_**

## uninstall

- **_npm un `<package>`_**

## update

- npm up **_`<package>`_**

## Flags<br>

**-S** is the same as _--save_, and **-D** is the same as _--save-dev_.

List globally installed packages<br>

- **_npm list -g --depth=0_**<br>

Uninstall global package<br>

- **_npm -g uninstall <name>_**<br>

Upgrade npm on Windows<br>

- **_npm-windows-upgrade<br>_**

Update global packages<br>

To see which packages need updating, use:<br>

- **_npm outdated -g --depth=0_**<br>

To update global packages individually you can use:

- **_npm update -g <package> <package> <package>_**

list available scripts to run

- **_npm run_**

Update npm

- **_npm install -g npm@latest_**

# On Windows,

- **_npm-windows-upgrade_**

Installed version<br>

- **_npm list #_** for local packages<br>

Node Version Manager nvm

nvm makes it easy to switch between different versions of Node.js.

Once nvm is installed, if one wants to install the latest version of Node v12 just run:

- **_nvm install 12_**

If there are multiple versions of Node.js installed on the workspace, one can switch to a specific
version by writing:

- **_nvm use 10.19.0_**

Make a Node version default

In order to set a default version of Node for your workspace, just type:

- **_nvm alias default 12_**<br>

Where the latest version of 12 is the version you want to be used by default.

- **_Update npm_**<br>

If Node is installed through nvm, it's good practice to update the version of npm with this command:

- **_nvm install-latest-npm_**
