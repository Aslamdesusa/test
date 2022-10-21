# Mobile Marketing Platform | Backend

A nice project with a nice description

---
## Requirements

For development, you will only need Node.js and a node global package, NPM, installed in your environement.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on macOs

  You can install nodejs and npm easily with brew install, just run the following commands.

      $ brew install nodejs
  
  NPM is included with Node. js installation. After you install Node. js, verify NPM installation by writing the following command in terminal or command prompt.

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line.

    $ npm install npm -g

---

## Database

    $ MongoDB ( To setup mongodb download database rs1 folder from drive If you don't have access, ask DevOps Engineer to provide access )
    $ Redis (Optional)
    $ Memcached

## Install

    $ git clone https://github.com/YOUR_USERNAME/PROJECT_TITLE
    $ cd PROJECT_TITLE
    $ npm install

## Configure app

Open `/backend-mmp/[environment].config.json` then edit it with your settings. You will need:

## Environment
    
    $ development
    $ staging
    $ production

## Run the project with nodemon
Nodemon is used for the development of applications based on node. js. It simply restarts the node application whenever it observes the changes in the file present in the working directory of your project.

    $ npm run start:nodemon:dev

## Run the project without nodemon
    
    $ npm run start:node:dev
