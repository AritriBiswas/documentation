### Now it is time that we design the frontend of our blockchain project. For that we choose one of the most popularly used JavaScript framework for building user interfaces, React.


#React

####React is a JavaScript library that eases the designing and building process of the user interface using JavaScript. React is a component based language where the developer writes code for an element of the page (For example, a Nav bar used in this project itself is an element) only once and exports it. 

In the course of developing all the pages required for the website, the developer only needs to import the js folder that contains the element and use it at any required position.

##Getting Started with React

####We directly jump into creating a react app, for that we need to install node through a simple command:


####Next, we install NPM, Node Package Manager by a simple command:



####NPM is used to manage dependencies for packages. If you were to unpack a framework and use it outside NPM, you would have to do this every time you want to update the framework. NPM does this for you. You always know what version you're on, and you can limit a dependency to a specific version.

####At this point we are ready to initiate our React application. In our project, we have two main directories that is the client and the truffle folder.
**Client : ** This is where our client side application will reside.
** Truffle : ** This directory where the solidity related files are stored.

So we make sure that our React files are created inside the client directory. (We change the current directory to client)

Here we type the command for creating the React app.


#### NPX, Node Package Execute  as we ust want to run the react application, we dont really the packages to be installed in our system. This is possible using NPX. It is a package runner that comes along with NPM.

These are the files and packages that should get inatalled once our command has run successfully.

Now enter the following command while in the same directory.


This command is very important as it installs all the dependenies that we will be requiring while building the interface.All the packages and their versions that get installed in the node_modules folder have their reference from a preexisting json file named package.json.


Once node_modules is installed successfully, enter the command

This should start our React app

We are now ready to start building our own user interface.

