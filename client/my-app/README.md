# Blog Website

## Overview

This project is a full-stack blog website that allows users to create, edit, and delete posts. The project features user authentication and verification, built using modern web development technologies including HTML, CSS, JavaScript, React.js, Node.js, Express.js, and MongoDB.

## Features

- User authentication and verification
- Create, edit, and delete blog posts
- Responsive design
- RESTful API

## Technologies Used

- Frontend:
  - HTML
  - CSS
  - JavaScript
  - React.js
- Backend:
  - Node.js
  - Express.js
- Database:
  - MongoDB
- Authentication:
  - JWT (JSON Web Tokens)
  
## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB (local or Atlas)

## Installation



### Frontend

1. Navigate to the frontend directory:
    ```sh
    cd ../client/my-app
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the React development server:
    ```sh
    npm start
    ```

## Project Structure

```plaintext
blog-website/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── .env
│   ├── server.js
│   └── package.json
└── frontend/
    ├── public/
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   ├── services/
    │   ├── App.js
    │   └── index.js
    ├── .env
    └── package.json
