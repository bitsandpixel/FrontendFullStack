# FrontendFullStack

## Table of contents
* [General info](#general-info)
* [Development Environment](#development-environment)
* [Setup](#setup)
    * [Useful Commands](#useful-commands)
        * [Installation](#installation)
        * [Version](#version)
        * [Functionality](#functionality)

## General info
*   A frontend full stack project course oon Course era.
*   URL: https://www.coursera.org/learn/html-css-javascript-for-web-developers
	
## Development Environment
Project is created with:
* [Visual Studio Code](#visual-studio-code) 
* [Node.js](#Node.js)
* [npm](#npm)
* [Browsersync](#browsersync)

## Setup
Install the tools in the exact order to avoid the problems further down the line.

### Visual Studio Code
*   How to install:
    * Follow the instructions in the given URL.
*   Installed Version: 1.60.1 
*   URL: https://code.visualstudio.com/download
*   Extensions:
    * Babel ES6/ES7
    * Path Intellisense
    * Auto Close Tag
    * Auto Complete Tag
    * Auto Rename Tag
*   Usage: Code Editor
*   Installation Dependency:
    * None

### Node.js
*   How to install:
    * Follow the instructions in the given URL.
*   Installed Version: 16.9.1
*   URL: https://nodejs.org/en/
*   Usage: 
    * to create a production web server
*   Installation Dependency:
    * None

### npm
*   How to install:
    * Node Package Manager will be installed along with [Node.js](#Node.js)
*   Installed Version: 7.24.0
*   URL: https://nodejs.org/en/
*   Usage: 
    * to install [Browsersync](#browsersync)
*   Installation Dependency: 
    * None

### Browsersync
*   How to install:
    * go to  [Installation](#installation) section for the command or 
    * Follow the instructions in the given URL. 
*   Installed Version: 2.27.5
*   URL: https://browsersync.io/
*   Usage: 
    * Time-saving synchronised browser testing is possible which eliminates the manual repetative tasks like live reloading.
    * Simple development http server with live reload capability.
    * Tests the action across devices and browsers over internet while developing on local machine.
*   Installation Dependency:
    * [Node.js](#Node.js)
    * [npm](#npm)
    * Restart Windows for yarn to completely configure itself.


### Useful Commands

* #### Installation
```
    To install npm globally
        npm install -g npm@7.24.0

    To install Browsersync globally
        npm install -g browser-sync
```
* #### Functionality
```
    To activate live-server on public folder inside indecision-app folder
        live-server public

    To view the commands you can run with babel
        babel --help
    
    To access the list of commands of yarn
        yarn help
    
    To get the information of specific command of yarn
        yarn help COMMAND
    
    To start a new project and to interactively create or update a package.json file
        yarn init

    To compile an input file to an output file using babel 
        babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch
```
* #### Version
```
        node -v 
        npm -v
        browser-sync --version
```



