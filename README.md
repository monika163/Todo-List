# Mern Blog App

This project is a full-stack web application built using the MERN stack – MongoDB, Express.js, React.js, and Node.js. It provides a platform for users to create, read, update, and delete blog posts.

Deployed link => https://mern-blog-app-1fip.onrender.com/

## Login and registration with MongoDB, Express, React & Nodejs (MERN).

- [Key Features](#key-features)
- [Technologies used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
- [Configuration and Setup](#configuration-and-setup)
- [📸 Screenshots](#screenshots)
- [Author](#author)

## Key Features

- User registration and login
- Authentication using JWT Tokens
- Story searching and pagination
- CRUD operations (Story create, read, update and delete)
- Upload user ımages and story ımages to the server
- Liking stories and adding stories to the Reading list
- Commenting on the story
- Skeleton loading effect
- Responsive Design

## Technologies used

This project was created using the following technologies.

#### Frontend

- [React js ](https://www.npmjs.com/package/react) - JavaScript library that is used for building user interfaces specifically for single-page applications
- [React Hooks ](https://reactjs.org/docs/hooks-intro.html) - For managing and centralizing application state
- [react-router-dom](https://www.npmjs.com/package/react-router-dom) - To handle routing
- [axios](https://www.npmjs.com/package/axios) - For making Api calls
- [Css](https://developer.mozilla.org/en-US/docs/Web/CSS) - For User Interface
- [CK-Editor](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/frameworks/react.html) - Rich Text Editor
- [uuid](https://www.npmjs.com/package/uuid) - For random id generator
- [React icons](https://react-icons.github.io/react-icons/) - Small library that helps you add icons to your react apps.

#### Backend

- [Node js](https://nodejs.org/en/) -A runtime environment to help build fast server applications using JS
- [Express js](https://www.npmjs.com/package/express) -The server for handling and routing HTTP requests
- [Mongoose](https://mongoosejs.com/) - For modeling and mapping MongoDB data to JavaScript
- [express-async-handler](https://www.npmjs.com/package/express-async-handler) - Simple middleware for handling exceptions inside of async express routes and passing them to your express error handlers
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - For authentication
- [Bcryptjs](https://www.npmjs.com/package/bcryptjs) - For data encryption
- [Nodemailer](https://nodemailer.com/about/) - Send e-mails from Node.js
- [Dotenv](https://www.npmjs.com/package/dotenv) - Zero Dependency module that loads environment variables
- [multer](https://www.npmjs.com/package/multer) - Node.js middleware for uploading files
- [slugify](https://www.npmjs.com/package/slugify) - For encoding titles into a URL-friendly format
- [cors](https://www.npmjs.com/package/cors) - Provides a Connect/Express middleware

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

![1 register](https://github.com/monika163/Mern-Blog-App/assets/61625011/9766236c-9329-492d-b06b-814946e9484a)

---

![2 login](https://github.com/monika163/Mern-Blog-App/assets/61625011/20cf6509-bcf8-4e91-ba15-99bf11d2c627)

---

![3 forget password](https://github.com/monika163/Mern-Blog-App/assets/61625011/0ee2abe7-a3c8-471e-8250-2cef1b43c6d5)

---

![4  blog](https://github.com/monika163/Mern-Blog-App/assets/61625011/65d74264-ed43-4061-9ebe-9b62de3e3849)

---

![5  blog details](https://github.com/monika163/Mern-Blog-App/assets/61625011/428390c6-0d1b-4a89-b02b-2bc904dd2076)

---

![6  comment](https://github.com/monika163/Mern-Blog-App/assets/61625011/0c9db441-8590-4212-8e04-2f6c83d1cee7)

---

![7  reading list](https://github.com/monika163/Mern-Blog-App/assets/61625011/a173b461-c25c-4964-b469-ef4d4aa05848)

---

![8  edit profile](https://github.com/monika163/Mern-Blog-App/assets/61625011/a571651b-c15b-410a-a583-53b535a93828)

---

![9  blog add](https://github.com/monika163/Mern-Blog-App/assets/61625011/17dd1d75-526f-4bfe-a080-9cc6cf62fa22)

---

![10  update password](https://github.com/monika163/Mern-Blog-App/assets/61625011/4cf8a6a6-c492-4d3b-8665-9676e7bfd1b3)

---

## Author

- Portfolio: [monika163](----)
- Github: [monika163](https://github.com/monika163)
- Linkedin: [monika163](https://www.linkedin.com/in/monika-dewangan-78a427149/)
