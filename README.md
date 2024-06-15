# Mern Blog App

This is a simple Todo List application built using the MERN stack. It allows users to add, update and delete tasks. The application uses a MongoDB database to store the tasks.

Deployed link : https://todo-list2-3pr5.onrender.com

## Todo List with MongoDB, Express, React & Nodejs (MERN).

- [Key Features](#key-features)
- [Technologies used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
- [Configuration and Setup](#configuration-and-setup)
- [📸 Screenshots](#screenshots)
- [Author](#author)

## Key Features

- Add new todo
- Delete todo
- Edit todo
- Filter todo by status (all todos, active todos, done todos)
- Removing all done todos.

## Technologies used

This project was created using the following technologies.

#### Frontend

- [React js ](https://www.npmjs.com/package/react) - JavaScript library that is used for building user interfaces specifically for single-page applications
- [React Hooks ](https://reactjs.org/docs/hooks-intro.html) - For managing and centralizing application state
- [react-router-dom](https://www.npmjs.com/package/react-router-dom) - To handle routing
- [axios](https://www.npmjs.com/package/axios) - For making Api calls
- [redux](https://www.npmjs.com/package/redux) - A JS library for predictable global state management
- [redux-thunk](https://www.npmjs.com/package/redux-thunk) - Thunk middleware for Redux. It allows writing functions with logic inside that can interact with a Redux store's dispatch and getState methods.
- [redux-devtools-extension](https://www.npmjs.com/package/redux-devtools-extension) - Developer Tools to power-up Redux development workflow or any other architecture which handles the state change
- [Css](https://developer.mozilla.org/en-US/docs/Web/CSS) - For User Interface

#### Backend

- [Node js](https://nodejs.org/en/) -A runtime environment to help build fast server applications using JS
- [Express js](https://www.npmjs.com/package/express) -The server for handling and routing HTTP requests
- [Mongoose](https://mongoosejs.com/) - For modeling and mapping MongoDB data to JavaScript
- [Dotenv](https://www.npmjs.com/package/dotenv) - Zero Dependency module that loads environment variables
- [cors](https://www.npmjs.com/package/cors) - Provides a Connect/Express middleware
- [body-parser](https://www.npmjs.com/package/body-parser) - It is responsible for parsing the incoming request bodies in a middleware before you handle it. It’s commonly used in web applications built with Express.js to handle form submissions, JSON payloads, and other types of request bodies.
- [concurrently](https://www.npmjs.com/package/concurrently) - allow coders to run multiple scripts with one command
- [nodemon](https://www.npmjs.com/package/nodemon) - an auto-refresh the server on code change

#### Database

- [MongoDB ](https://www.mongodb.com/) - It provides a free cloud service to store MongoDB collections.

## Configuration and Setup

### Setup Config.env file

```shell
NODE_ENV = development
PORT =5000
URI =http://localhost:3000
MONGO_URI =
JWT_SECRET_KEY =
JWT_EXPIRE = 60m
RESET_PASSWORD_EXPIRE = 3600000

# Nodemailer

SMTP_HOST =smtp.gmail.com
SMTP_PORT =587
EMAIL_USERNAME = example@gmail.com
EMAIL_PASS = your_password
```

### Installation

```shell
Install dependencies for server
npm install

Install dependencies for client
cd client
npm install

Run the client & server with concurrently
npm run dev

Run the Express server only
npm run server

Run the React client only
npm run client

Server runs on http://localhost:5000 and client on http://localhost:3000
```

## Screenshots

![1 added todos](https://github.com/monika163/Todo-List/assets/61625011/9cc32aea-7bf3-49a8-9187-15f8465b4bbe)

---

![2  addded all todos](https://github.com/monika163/Todo-List/assets/61625011/b60ae33d-a556-4027-b258-23ff97faffa9)

---

![3  active todos](https://github.com/monika163/Todo-List/assets/61625011/daf2f934-5287-400c-bb8b-0664df98ccb0)

---

![4  done todos](https://github.com/monika163/Todo-List/assets/61625011/66190add-a7a9-4a3e-8951-9687c6dcdeae)

---

![5  blog details](https://github.com/monika163/Mern-Blog-App/assets/61625011/428390c6-0d1b-4a89-b02b-2bc904dd2076)

---

## Author

- Portfolio: [monika163](----)
- Github: [monika163](https://github.com/monika163)
- Linkedin: [monika163](https://www.linkedin.com/in/monika-dewangan-78a427149/)
