# Heart Rate Calculator

Calculate heart rate by heart rate statistics data stored in json file.

---
## Requirements

For development, you will only need Node.js and a node global package  installed in your environement.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###
---

## Clone Project

    $ git clone https://github.com/anil127/heartrate-calculator.git
    $ cd heartrate-calculator

## Running the project

    $ npm run app
After running this commad you can see generated `output.json` file in the same directory.

## About Project

### Used Modules

| Module | Description |
| --- | --- |
| fs | Node.js file system module allows you to work with the file system on your computer. |

### Functions

| Function | Description |
| --- | --- |
| calculateMedian | Calculate median by provided input |