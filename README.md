# PhotoMessage
Photo Message is a Progressive Web Application which uses google workbox. It is an messaging app where users send messages with photo.
Service worker files are built using sw_build.js file which uses workbox-build to dynamically create service worker files.
I am using workbox via cdn

## App Dependencies
### yarn
npm install --global yarn (If you don't want to install it globally remove --global)

### Bootstrap
yarn add bootstrap

### jquery
yarn add jquery 

### Express
yarn add express

### Toastr
yarn add toastr

### Socket.io
yarn add socket.io

### Workbox Build
yarn add workbox-build

## I have added some scripts in package.json

### To start the server
yarn start

### To build service worker files using workbox build
yarn build
