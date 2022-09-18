# Social Network API

I build an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

I used use Express.js for routing, a MongoDB database, the Mongoose ODM, and Moment.js as a date library to format timestamps.

## About

GIVEN a social network API, WHEN you enter the command to invoke the application, THEN the server is started and the Mongoose models are synced to the MongoDB database.

WHEN you open API GET routes in Insomnia for users and thoughts, THEN the data for each of these routes is displayed in a formatted JSON. WHEN you test API POST, PUT, and DELETE routes in Insomnia, THEN you are able to successfully create, update, and delete users and thoughts in my database. Also WHEN you test API POST and DELETE routes in Insomnia, THEN you are able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list.

## How to Use

You will first need to download [MongoDB](https://coding-boot-camp.github.io/full-stack/mongodb/how-to-install-mongodb).

Next you will need to clone [my GitHub Repository](https://github.com/amymgardiner/Social-Network-API).

Once you're in the file relating to my code, in your command line you will enter:

`npm install`

which installs the dependencies to the local node_modules folder. By default, npm install will install all modules listed as dependencies in package.json.

Finally, the application will be invoked by using the following command:

`npm start`
