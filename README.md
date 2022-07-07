#Gold Digger App


## App Functionality 

A budget tracking app that is downloadable through the browser that helps the user keep track of their deposits and expenses. The app stores data locally through the help of a service wroker to maintain data offline. This also lets the user interact with their data while offline, making it helpful for those with unreliable internet.

## Technologies Used
```md
- Express
- MongoDB
- Node.js
```

## Demo

<img src = "public\images\README.png">

[Check out the app functionality on Heroku!](https://tranquil-eyrie-52302.herokuapp.com/)


## Installation

This project requires Node.js and other dependencies

[How to install Node](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)


Navigate to the directory you would like to use using the CLI and then clone this repository:

```bash
git clone git@github.com:jefid/gold-digger.git
```

Create `.gitignore` to include the following:

```bash
node_modules
.DS_Store
package-lock.json
```
You will need to install MongoDB

[Installation guide for Mongo](https://www.mongodb.com/docs/manual/installation/)

Open your IDE and use these commands to install _all_ the necessary packages:

```bash
npm i express mongoose
npm init
```

`npm init` will create your `package.json` file.

```json
"scripts": {
    "start": "node server.js",
}
```

In the terminal, start the MongoDB database

```mysql
mongod;
```

Finally, start the server from the command line:

```bash
npm start
```



## Documentation

- [npm](https://docs.npmjs.com/)
- [Express](https://expressjs.com/en/4x/api.html)
- [Mongoose](https://www.mongodb.com/)


## Feedback

Have something you'd like to add?<br>
Feel free to contact me via email!<br>

<a href="mailto:jquandt411@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
 </a>
