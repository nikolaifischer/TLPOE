# The Largest Planet on Earth Homepage 

This repository includes the code of the Homepage for Munich-based band The Largest Planet on Earth.

![Screenshot](./img/TLPOE_Screenshot.PNG)

For live version see: http://www.thelargestplaneton.earth

## Overview
This is a very lightweight website using only HTML, CSS and a little JS. No database is needed to run it. Changes in content (they are infrequent) are committed directly to the code base.

## Getting Started
### Prerequisites
All that is needed is a arbitrary http server on the machine hosting the website. The following instructions use node.js with the http-sever package. Any other server like Apache (e.g. XAMPP) or Python's http.server are also possible.
#### Install node.js
Download & Install [node.js](https://nodejs.org/)
#### Install http-server using npm
Start a shell and input this:

    npm install -g http-server
#### Download this repository
Download or clone this repository. If you downloaded the zip archive, be sure to unzip it.
#### Start the Server
Start a shell and navigate to the folder containing the index.html file. Input this:

    http-server -p 80

#### Open the website
Start a browser and navigate this address:
    http://localhost:80

## Production
In production on a linux system, the usage of the npm package **forever** is recommended:

To start:

    forever start /usr/local/bin/http-server /var/www/TLPOE/
