WebSocket Chat Implementation for Node
=================================================


Overview
--------
This is a prototype chat for the website. 

Each client has its own chat.
Administrator can personally answer for each one of them.
Future plans are to implement it as a plugin on the website to provide better UI experience with interactive chat with site owners\admins\etc...

Demo
--------
[Current version demo on Heroku](https://damp-reaches-19849.herokuapp.com/ "Heroku")

Documentation
=============

Changelog
---------

***Current Version: 1.0.2*** — Released 2019-04-25

Now using Quasar CLI, Webpack, Babel. Project is now compiling from sources

Installation
------------
  
Download or clone repository, then run:

    $ npm install
    
    $ quasar build    

Current Features:
-----------------
- Single page to choose chat mode
- Active chat card highlighting
- Dynamically adding new client chats on the admin page
- User input data filtering

Known Issues/Missing Features:
------------------------------
- Automatically remove closed chats (where user left their chat page)
- Load message history from server for active chats when administrator connected
- Only one administrator connection is allowed for now
- If try to connect as administrator again the logic for that chat will be incorrect
- User registration and login
- Administrator secure login

Detailed info about bugs is in the bugs.txt

Usage
==============

    $ node chatServer.js

You can specify port number between 0 and 65535 as:

    $ node chatServer.js [portNumber]
--------------



