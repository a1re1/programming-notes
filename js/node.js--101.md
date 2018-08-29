# Node.js General Notes

## Why do I need to do this?
Node requires 'http' module by default as part of the library in order to run a node server

require({module-name}) keyword used to import node modules for use in different modules
generally store require object as const object

ES6 = ECMAScript 6

## Common modules/functions
'fs' file-system used to:
 - read
 - create
 - update
 - delete
 - rename

'http' module with support to transfer data over hypertext transfer protocol in order to handle GET and POST requests as well as sending responses back to the web client

'url' uniform resource loader with module methods that can parse address parts as properties

setTimeout();
clearTimeout();
setInterval();
clearInterval();

can be accessed via global object;

'path' module is useful to work with file paths

var variable = "String"
console.log(`Message ${variable}`);


## Helpful methods
console.log("");
JSON.stringify();


## Events
'events' module
const EventEmitter = require('events') // Class
const emitter = new EventEmitter(); // object

emitter.on('messageLogged', (arg) => { // function(arg){
    console.log('Listener called', arg); // what to do when event is triggered
}); // AddListener, adding an event listener, must register event before raising event

emitter.emit('messageLogged', {id: 1, url: 'http://'}); // event will be raised, you can return objects when raising argument

emitter object should only be declared once in project
http.server is an EventEmitter

## Classes
class ClassName{ //extends EventEmitter
  function(){

  }
}


## Practical examples
Express.js is more practical for servers than building out your own app.js to handle routes

## Gulp
