# simplechatapp
The first goal is to setup a simple HTML webpage that serves out a form and a list of messages. 
We’re going to use the Node.JS web framework express to this end. Make sure Node.JS is installed.
First let’s create a package.json manifest file that describes our project. I recommend you place
it in a dedicated empty directory (I’ll call mine chat-example).
Now, in order to easily populate the dependencies with the things we need, we’ll use npm install --save:
>npm install --save express
Now that express is installed we can create an index.js
Then write the code that was given in index.html and index.js.
Integrating Socket.IO
Socket.IO is composed of two parts:
A server that integrates with (or mounts on) the Node.JS HTTP Server: socket.io
A client library that loads on the browser side: socket.io-client
>npm install --save socket.io
This is all about creating a simple chat using locolhost...
