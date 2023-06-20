# HTML-SASS
This is my repository of the projects I've made using HTML, SASS and a bit of JS. If you need more information, contact me.


This repository contains a web project developed using HTML, Sass, CSS, and a little bit of JavaScript.

## Web Development Setup

### Requirements

Before getting started, make sure you have the following requirements installed:

- [Visual Studio Code](https://code.visualstudio.com/) (Recommended code editor)
- [Git Bash](https://gitforwindows.org/) (Terminal for Windows) / Terminal (for macOS/Linux)
- [Node.js](https://nodejs.org/) (JavaScript runtime environment)

### Installation

Follow the steps below to set up your development environment:

1. Download and install Visual Studio Code from [its official website](https://code.visualstudio.com/).

2. Download and install Git Bash for Windows from [its official website](https://gitforwindows.org/). If you're on macOS or Linux, you can use the built-in terminal.

3. Download and install Node.js from [its official website](https://nodejs.org/). Node.js includes npm (Node Package Manager), which will be used to install project dependencies.

4. Clone this repository by running the following command in your terminal:

git bash

`git clone https://github.com/JorgeMunarriz/HTML-SASS.git`

### Recommended Extensions for Visual Studio Code
Make sure you have the following extensions installed in Visual Studio Code to enhance your web development experience:

Live Server - Serves and automatically updates your web application in real-time as you make changes. Link Vs Marketplace: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
Live Sass Compiler - Automatically compiles your Sass files to CSS in real-time. Link Vs Marketplace: https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass
Prettier - Automatically formats your HTML, CSS, and JavaScript code to maintain consistent styling. Link Vs Marketplace: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
HTML to CSS autocompletion - Provides completion suggestions for classes and ids from markup documents to stylesheets. Link VS Marketplace: https://marketplace.visualstudio.com/items?itemName=solnurkarim.html-to-css-autocompletion
Material Icon Theme - Get the Material Design icons into your VS Code. Link Vs Marketplace: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
CSS Flexbox Cheatsheet - VS Code extension that lets you open a flexbox cheatsheet directly in the editor. Link Vs Marketplace: https://marketplace.visualstudio.com/items?itemName=dzhavat.css-flexbox-cheatsheet
Image Preview - Shows image preview in the gutter and on hover. Link Vs Marketplace: https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview

Paquete de idioma español para VS Code
El paquete de idioma español proporciona una experiencia de UI localizada para VS Code.

Uso
Puede invalidar el idioma predeterminado de la interfaz de usuario si establece explícitamente el idioma de VS Code con el comando "Configure Display Language". Presione "Ctrl+Mayús+P" para que aparezca la instancia de "Paleta de comandos" y empiece a escribir "display" para filtrar y mostrar el comando "Configure Display Language". Presione "Entrar" y se mostrará una lista de los idiomas instalados por configuración regional, con la actual resaltada. Seleccione otra "configuración regional" para cambiar el idioma de la interfaz de usuario. Vea Docs para más información. Link Vs Marketplace:  https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-es

### Project Usage
Open Visual Studio Code and navigate to the project folder.

Install project dependencies by running the following command in the terminal:

 git bash

`npm install`

Launch the local server to view your project in the browser using Live Server.

Start editing the HTML, Sass, CSS, and JavaScript files according to your needs.

### Contribution
If you wish to contribute to this project, you can follow these steps:

Fork this repository.

Create a new branch for your changes:

git bash

`git checkout -b your_branch_name`

Make your modifications and commit them:

git bash

`git commit -m "Description of your changes"`

Push your changes to the remote repository:

git bash

`git push origin your_branch_name`


### Extra configuration
To install the npm, pnpm, and Yarn package managers on your system, follow the instructions below for the tool you want to use:

Installing npm (Node Package Manager)
npm is automatically installed along with Node.js. Follow these steps to install Node.js and get npm:

Download Node.js from its official website and choose the appropriate version for your operating system.

Run the downloaded installer and follow the instructions in the installation wizard.

Once the installation is complete, open a new terminal window and verify that Node.js and npm are installed correctly by running the following commands:

git bash

`node --version`
`npm --version`

Both commands should display the respective versions of Node.js and npm without any errors.

Installing pnpm
To install pnpm, you can use npm by running the following command in your terminal:

git bash

`npm install -g pnpm`

This will install pnpm globally on your system. Verify the installation by running the following command:

git bash

`pnpm --version`

If the command displays the pnpm version without any errors, it means the installation was successful.

Installing Yarn
To install Yarn, follow the steps below based on your operating system:

Windows
Download the Yarn installer from its official website.

Run the downloaded installer and follow the instructions in the installation wizard.

Once the installation is complete, open a new terminal window and verify that Yarn is installed correctly by running the following command:

git bash

`yarn --version`

It should display the Yarn version without any errors.

macOS
Open the terminal and run the following command to install Yarn using Homebrew:

git bash

`brew install yarn`

Verify the installation by running the following command:

git bash

`yarn --version`

It should display the Yarn version without any errors.

Linux
On Linux, you can install Yarn using the apt or apt-get package manager. Follow these steps:

Open the terminal and run the following commands to add the Yarn repository:

git bash

`curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -`
`echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list`

Update the packages and install Yarn by running the following commands:

git bash

`sudo apt update`
`sudo apt install yarn`

Verify the installation by running the following command:

git bash

`yarn --version`

It should display the Yarn version without any errors.

With these instructions, you'll be able to install npm, pnpm, and Yarn on your system according to your preferences. Remember that you only need to choose one of these package managers to use in your projects.