# setupbackend

setupbackend is a Node.js package designed to automate the tedious process of setting up a backend project. With just a few simple commands, you can create a production-grade folder structure, essential files, and install necessary packages, saving you valuable time and effort.

## Installation

To use setupbackend, follow these simple steps:

1. Create a `setup.js` file in your project directory.
2. Run `npm init -y` to initialize a new Node.js project.
3. Install setupbackend by running `npm i setupbackend`.
4. Add the following code to your `setup.js` file:
```javascript
const setupbackend = require('setupbackend');
setupbackend();
```
4. Run `setup.js` file:
```javascript
node setup.js
````

## Features

- Creates essential files: index.js, app.js, .env, and .gitignore
- Sets up an Express boilerplate inside index.js for quick server setup
- Generates a .gitignore file tailored for Node.js projects
- Establishes a production-grade folder structure for scalability and organization
- Installs over 10 essential packages including:
  - Express
  - Mongoose
  - Cors
  - Dotenv
  - JWT
  - Bcrypt
  - Multer
  - Cookie-parser
  - Cloudinary
  - Prettier
  - Nodemon
- Automatically deletes setup file to keep your project clean
- Completion of setup within 15 to 30 seconds

