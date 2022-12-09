# Wheather_App

Wheather_App it's a one-page site for viewing the weather in your city or anywhere else on the planet

## Technologies & Tools Used:

- Java Script
- HTML
- CSS
- React.js
- Tailwind CSS
- React-Toastify

## Description 
On this site you can find out the weather for 5 hours ahead and 5 days ahead for your location or in any other city you want, also the site changes the design at low and high temperature
## Installation

Clone my project to your desktop:
   - Click “Code” and copy the given URL.
   - Open "Terminal" and change the current working directory to the location for a cloned project.
   - Type 
   
bash 
   git clone {repository URL}
## Install Tailwind CSS
Install tailwindcss via npm, and create your tailwind.config.js file.

Terminal
```
npm install -D tailwindcss
npx tailwindcss init
```

Configure your template paths
Add the paths to all of your template files in your tailwind.config.js file.

tailwind.config.js
```/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
Add the Tailwind directives to your CSS
Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.

src/input.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
Start the Tailwind CLI build process
Run the CLI tool to scan your template files for classes and build your CSS.

Terminal
```
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch  
 ```
## Installation react-toastify
```
$ npm install --save react-toastify
$ yarn add react-toastify
```
## Requirements 
For development, you will need Node.js and  Gulp installed on your environement.

### Node
[Node](https://nodejs.org/en/) is really easy to install & now include [NPM](https://www.npmjs.com). You should be able to run the following command after the installation procedure below.

bash 
$ node --version
v0.10.24

$ npm --version
1.3.21



#### Node installation on OS X

You will need to use a Terminal. On OS X, you can find the default terminal in /Applications/Utilities/Terminal.app.

Please install [Homebrew](https://brew.sh) if it's not already done with the following command.

bash 
$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

If everything when fine, you should run
bash
brew install node

#### Node installation on Linux
 bash
sudo apt-get install python-software-properties
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs

#### Node installation on Windows
Go on official [Node.js website](https://nodejs.org/en/) & grab the installer. Also, be sure to have git available in your PATH, npm might need it.

### Gulp 
- Check for node, npm, and npx
 bash
node --version
npm --version
npx --version

If they are not installed, follow the instructions [here](https://nodejs.org/en/).

- Install the gulp command line utility
 bash
npm install gulp -g


### Project Dependencies
Install project dependencies
bash
npm install 

  OR use this command to speed up installation
bash
npm ci 

(about the differences between npm install and npm ci you can read [here](https://docs.npmjs.com/cli/v8/commands/npm-ci))

### Start the development environment 
bash 
npm start

### Simple build for production
bash
npm run build
