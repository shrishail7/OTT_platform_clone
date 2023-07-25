# OTT_platform_clone

# Description:
This project is a clone of a popular Over-The-Top (OTT) platform built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The application allows users to browse and stream a collection of movies, TV shows, and other video content. It also includes user authentication, allowing registered users to create accounts, save favorites, and manage their profile settings.

# Features:
Browse Content: Users can explore the collection of movies, TV shows, and other video content available on the platform.

Search Functionality: Users can search for specific titles or keywords to find relevant content.

Video Streaming: Users can watch videos through the built-in streaming player.

Favorites: Registered users can mark videos as favorites to access them later conveniently.

User Profile: Users can manage their profile information and update account settings.

Installation:

Clone the repository

bash
Copy code
git clone https://github.com/shrishail7/OTT_platform_clone.git

Navigate to the project directory:

bash
Copy code
cd ott-platform-clone
Install server dependencies:

    "axios": "^1.2.0",
    "cookie-parser": "^1.4.6",
    "cors": "^2.8.5",
    "dotenv": "^16.0.3",
    "express": "^4.18.2",
    "express-validator": "^6.14.2",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^6.7.5",
    "nodemon": "^2.0.20"
  

bash
Copy code
cd server
npm install
Install client dependencies:

    "@emotion/react": "^11.10.5",
    "@emotion/styled": "^11.10.5",
    "@fontsource/roboto": "^4.5.8",
    "@mui/icons-material": "^5.10.16",
    "@mui/lab": "^5.0.0-alpha.110",
    "@mui/material": "^5.10.16",
    "@reduxjs/toolkit": "^1.9.1",
    "@testing-library/jest-dom": "^5.14.1",
    "@testing-library/react": "^13.0.0",
    "@testing-library/user-event": "^13.2.1",
    "axios": "^1.2.0",
    "dayjs": "^1.11.6",
    "formik": "^2.2.9",
    "query-string": "^7.1.3",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-redux": "^8.0.5",
    "react-router-dom": "^6.4.4",
    "react-scripts": "5.0.1",
    "react-toastify": "^9.1.1",
    "swiper": "^8.4.5",
    "web-vitals": "^2.1.0",
    "yup": "^0.32.11"

bash
Copy code
cd client
npm install
Create a .env file in the server directory and provide the necessary environment variables, such as database connection details, JWT secret, etc.

.env example

  MONGODB_URL=
  
  PORT=
  
  TOKEN_SECRET_KEY=
  
  TMDB_BASE_URL=
  
  TMDB_KEY=


# Technologies:
MongoDB: NoSQL database for storing video content and user data.

Express.js: Backend framework for handling server-side logic and API routes.

React.js: Frontend library for building user interfaces.

Node.js: JavaScript runtime for executing server-side code.

JWT Authentication: JSON Web Tokens for user authentication.

Axios: HTTP client for making API requests to the server.


# Contributing:
We welcome contributions to improve the project. If you find any issues or want to add new features, feel free to open a pull request. Please follow the standard coding guidelines and commit message conventions.


Feel free to customize this readme file based on your specific project requirements and add any other relevant sections or details that you think would be helpful for other developers or users. Happy coding!





