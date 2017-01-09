# GameConnect

### Members
- David Boschwitz
- Ryan Gallus
- Michael Rhodas
- Sam Jackson

GameConnect is a platform for playing simple, web-based games on your PC while using your phone as a wireless controller. GameConnect games work on any modern browser and the app is available on all major platforms.

# Modules

## PC Client
The PC Client module, otherwise known as the Dart Client, is the GameConnect main web application front-end.

It is the web interface users will see when visiting the GameConnect website (currently offline).

The readme.md for the PC Client module can be found here:  [client readme](client/readme.md)

## Controller
The Controller module, otherwise known as the Cordova Client, JS Client, or Controller Client, is the "hardware interface" for GameConnect.

It is the mobile application users will use to make inputs on GameConnect. The controller application was built using Apache Cordova, which creates a native wrapper app for all major phone platforms.

The readme.md for the Controller module can be found here:  [controller readme](controller/readme.md)

## Server
The Server module is a part of the backend for GameConnect.  It drives communication and state changes for the two client modules.

The readme.md for the Server module can be found here:  [server readme](server/readme.md)

## Database
This application currently has no database, but one may be added in future development.  The Database module will be part of the backend for GameConnect.

##### Note
GameConnect was originally developed on GitLab and eventualy moved to GitHub. As a result, commits do not reflect actual contributions.
