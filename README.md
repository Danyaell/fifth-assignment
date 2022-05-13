# Fifth Assignment

## How to run

This node proyect has use the nodemon and express libraries just to execute the enviroment, using the next command:
#### npm i nodemon express
but, actually you just need to use
####
    npm i

After all node_modules install, you can run the proyect using
####
    npm start
This will run the application.

## How it works

We have two asynchronous functions, our two codes. These share 6 variables, wich are ' x, y, z, c, d, e '. Both functions just realize random arithmetic operations, and they call each other.

The first code use a ' setTimeout( ) ' just to make more interesting the example, we see how the asynchronous of this function is affected by the second one.