# EduPulse LMS

EduPulse is a Learning Management System (LMS) designed to provide a seamless and interactive learning experience for students and instructors. This project is built using modern web technologies including React, Node.js, Express, and MongoDB.

## Table of Contents

- Features
- Installation
- Usage
- Folder Structure
- Environment Variables
- Contributing
- License

## Features

- User Authentication (Login, Signup, Logout)
- Course Management (Create, Edit, Delete Courses)
- Lecture Management (Create, Edit, Delete Lectures)
- User Profile Management
- Dark Mode Support
- Payment Integration with Stripe
- Cloudinary Integration for Media Uploads

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/edupulse.git
   cd edupulse
2. Install dependencies for both client and server:
    cd client
    npm install
    cd ../server
    npm install
3. Create a .env file in the server directory and add the following environment variables:
    PORT=8080
    MONGO_URI=your_mongodb_uri
    SECRET_KEY=your_secret_key

    # Cloudinary
    API_KEY=your_cloudinary_api_key
    API_SECRET=your_cloudinary_api_secret
    CLOUD_NAME=your_cloudinary_cloud_name

    # Stripe
    STRIPE_SECRET_KEY=your_stripe_secret_key

## Usage
1. Start the server:
    cd server
    npm start
2. Start the client:
    cd client
    npm run dev
3. Open your browser and navigate to http://localhost:3000.

## Folder Structure
client/
  .gitignore
  components.json
  eslint.config.js
  index.html
  jsconfig.json
  package.json
  postcss.config.js
  public/
    vite.svg
  README.md
  src/
    app/
    App.css
    App.jsx
    assets/
    components/
    DarkMode.jsx
    features/
    index.css
    layout/
    lib/
    main.jsx
    pages/
  tailwind.config.js
  vite.config.js
README.md
server/
  .env
  .gitignore
  controllers/
    course.controller.js
    ...
  database/
    db.js
  index.js
  middlewares/
    ...
  models/
    ...
  package.json
  routes/
  uploads/
  utils/

## Environment Variables
The following environment variables need to be set in the .env file in the server directory:

>PORT: The port on which the server will run.
>MONGO_URI: The MongoDB connection string.
>SECRET_KEY: The secret key for JWT authentication.
>API_KEY: The Cloudinary API key.
>API_SECRET: The Cloudinary API secret.
>CLOUD_NAME: The Cloudinary cloud name.
>STRIPE_SECRET_KEY: The Stripe secret key for payment processing.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.