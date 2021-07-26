# BudgetTracker
An application that allows user to input income and expenses seamlessly regardless of internet connection.

## Description
This application is a site that allows users to track their money regardless of internet connection. The online/offline capabilities is a huge benifit to travellers or anyone on-the-go that wants to be conscious of their spending and budget but may not be able to rely on constant internet connection. IndexedDB is used to save each transaction from the user, therefore when the user is reconnected to the internet all the offline transactions are automatically added. Building this application required experience with Javascript and Express and an understanding of how to use MongoDB and Mongoose. MongoDB generates the database with a Mongoose schema while Express handles the routes. In order to run this application on Heroku, MongoDB Atlas was required to access the database while on a live server.

## Installation
This application does not require any installation and can be accessed here: [Budget Tracker](https://heathers-budget-tracker.herokuapp.com/)

If you would like to install the application locally, clone this application onto your machine through GitHub, then open it in the command line and run the command "npm install" to make sure all the features are installed for the application locally. Run the command "npm run seed" and set up your local MongoDB as it pertains to the app. Next, run the command "node server.js" to begin using it on your browser.

## Usage
Below are screenshots of the working application.
![screenshot1]()

## Credits
Thank you to Penn LPS Coding Bootcamp, instructors, peers, [JavaScript](https://www.javascript.com/), [Node.JS](https://nodejs.org/en/), [NPM](https://www.npmjs.com/) and its packages, [Express.js](https://expressjs.com/), [MongoDB](https://www.mongodb.com/), [Mongoose](https://mongoosejs.com/), [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) & [Robo3T](https://robomongo.org/), and Heroku.

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## How to Contribute
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](code_of_conduct.md)

Contact me @heatherloisejackson on GitHub
