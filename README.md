# Learning Node and Express

This is a set of lessons that will walk you through learning [Node.js](https://nodejs.org/en/) and [Express](https://expressjs.com/).

* [Overview](/OVERVIEW.md): Discusses what Node.js and Express do

* [Installation](/INSTALLATION.md): Discusses how to install Node.js and Express

* [Lesson 1](/lesson1/README.md): A Hello World for Node.js

* [Lesson 2](/lesson2/README.md): A help ticket server (using Node.js, Express) and front end (using Vue CLI)


### Note for Running (to myself)
To get lesson 2 running, you need to get both the front and backend servers running on localhost 8080 and 3000 respectively (there's already a file in the frontend config that allows us to proxy requests to localhost:3000 for requests. Do node tickets.js to get the backend started and run npm serve to get the frontend started. Make sure to do npm install in both first to ensure the necessary node_modules packages are there (and try doing npm install within node_modules if still getting issues). 
