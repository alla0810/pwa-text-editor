# PWA-TEXT-EDITOR  ![License](https://img.shields.io/badge/License-MPL_2.0-brightgreen.svg)

## Description

This program is to create notes or code snippets with or without an internet connect to retrieve them for later use.


## Features

GIVEN a text editor web application

* WHEN you oepn your application in your editor, THEN you should see a client server folder structure

* WHEN you run `npm run start` from the root directory, THEN you find that your application should start up the backend and serve the client

* WHEN you run the tet editor application from your terminal, THEN you find that your JavaScript files have been bundled using webpack

* WHEN you you run your webpack plugins, THEN you find that you have a generated HTML file, service worker, and a manifest file

* WHEN you use next-gen JavaScript in your application, THEN you find that the text editor still functions in the browser without errors

* WHEN you open the text editor, THEN you find that IndexedDB has immediately created a database storage

* WHEN you enter content and subsequently click off of the DOM window, THEN you find that the content in the text editor has been saved with IndexedDB

* WHEN you reopen the text editor after closing it, THEN you find that the content in the text editor has been retrieved from our IndexdDB

* WHEN you click on the Install button, THEN you download your web application as an icon on your desktop

* WHEN you load your web application, THEN you should have a registered service worker using workbox

* WHEN you register a service worker, THEN you should have your static assets pre cached upon loading along with subsequent pages and static assets

* WHEN you deploy to Render, THEN you should have proper build scripts for a webpack application


## Installation on your local machine
After downloading from GitHub, you can run this program on your local machine by following the procedure below:
1. From a terminal, log into your mySQL account by using `mysql -u ${your login name} -p`.
2. Inside logged mySQL terminal, type `source ${downloaded-application-path}/db/schema.sql`.
3. Open another terminal to run javascript e-commerce back-end server application.
4. Run `npm run seed` to seed data. Seed data create 5 categories, 5 product and 8 tags. 
5. Run `nodemon server.js` to run backend server on your local machine.
6. From Insomnia, send Restful API queries.

## Technologies used
1. Express.js (https://expressjs.com/)
2. concurrently (https://www.npmjs.com/package/concurrently)
3. nodemon (https://www.npmjs.com/package/nodemon)
4. webpack (https://webpack.js.org/) 
5. CodeMirror Themes (https://codemirror.net/5/index.html)
6. idb (https://javascript.info/indexeddb)
7. Babel (https://babeljs.io/)

## Source Code References
  This project has used some reference codes from the following sites

   * https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-07-2023-U-LOLC.git   


## Contact
  * Author: Kyosook Shin
  * Author's Email: kyosook.shin@gmail.com  
  * GitHub: https://github.com/alla0810/pwa-text-editor


## Screenshot  

<img src='./images/screen1.png' width="800">  
<img src='./images/screen2.png' width="800">
<img src='./images/screen3.png' width="800">  
<img src='./images/screen4.png' width="800">  
<img src='./images/screen5.png' width="800">  
