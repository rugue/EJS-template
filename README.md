## ejs-template: A Simple EJS Project

This project demonstrates a basic setup for using EJS (Embedded JavaScript) templating with Express.js in a Node.js application.

### Getting Started

Clone this repository or download the files.
Install the project dependencies:

```bash
Bash
npm install
```

### Running the application

1. Start the development server:

```bash
npm start
```

This will start the server on port 8000. You can access the application in your browser at http://localhost:8000/.

2. For development with automatic restarts on file changes:

```bash
npm dev
```

### Project Structure

The project consists of the following files and folders:

- app.js: This is the main server-side script that uses Express.js to handle incoming requests and render EJS templates.
- index.ejs: This is the main template file for your website's homepage.
- partials/header.ejs: This is a partial template that contains the website header and can be included in other templates.
- package.json: This file specifies project metadata, dependencies, and scripts.

### Using EJS Templates

The `app.js` file configures Express to use EJS as the view engine and sets the views directory. The index.ejs file demonstrates how to embed JavaScript expressions (<%= %>) and loops (<% %>) within HTML code.

### Dependencies

This project uses the following npm packages:

- express: A popular Node.js web framework.
- ejs: A templating engine that allows embedding JavaScript code within HTML templates.
