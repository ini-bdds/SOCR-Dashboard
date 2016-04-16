Dashboard-Lab
=============

This webapp combines and integrates multiple socioeconomic and medical datasets using big data analytics,
in order to provide a lightweight, scalable platform for drawing inferences related to medical care,
sociology, and economy in the United States.

To run this webapp locally, you must first install node

Running the Webapp Locally
==========================

1. in a command prompt navigate to the *server/mongodb/bin* folder, and run mongod: `mongod --dbpath ../data`

2. navigate to the root directory of the project in node, and run `npm install`

2. once dependencies are installed, launch node server: `npm start`

3. navigate to selected address in browser to launch webapp (default is [http://localhost:3000/](http://localhost:3000/))
