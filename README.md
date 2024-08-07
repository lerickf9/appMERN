Primeros pasos para el proyecto MERN
1.- Carpeta "Backend"
2.- Terminal: 
npm init
auth-kit-server
npm i  nodemon express mongose dotenv bcrypt
3.- Crear carpetas: 
controllers
middleware
helpers
models
routes
4.- crear archivo server.js
5.- Modificar el package.json de la siguiente forma
//
  "name": "auth-kit-server",
  "version": "1.0.0",
  "main": "server.js",
  "type": "module",
  "scripts": {
    "start": "nodemon server.js" //nodemon no es necesrio en la version 22.. de node js
  }

