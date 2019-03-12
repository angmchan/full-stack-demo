# STEP 1: Creating a basic server

We will now install the necessary packages and create the necessary files for a basic server.

# Installing the necessary packages

To create the most basic server, we need to install `ExpressJS`:

`npm install express --save

#### An aside on dependencies:
Running `npm i -S express` is the same as the above. `--save` adds the specified dependencies to our `package.json`. It is best practice to include all of the dependencies required for our program to run in our package.json. 

Libraries that are not function critical but are critical during the development process will be added to the developer dependencies by using `--save-dev` or `-D`.

# Creating the Server
First, let's follow the principle of separation of concerns and create the `server` folder. This folder will hold everything related servers including models, routes, templates, etc.

Within the `server` folder, create a `server.js` file.

We will then build the most basic server inside of `server.js`.