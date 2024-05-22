# MERN Stack E-commerce Project

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Technologies Used](#technologies-used)
6. [API Documentation](#api-documentation)
7. [Features](#features)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction
This is a full-fledged e-commerce application built using the MERN stack (MongoDB, Express, React, Node.js). The application is divided into three main folders: `frontend`, `backend`, and `admin`. This project aims to provide a robust and scalable e-commerce platform with user authentication, product management, order processing, and an admin panel for managing the application.


## Installation
Follow these steps to set up the project locally:

### Prerequisites
- Node.js
- npm or yarn
- MongoDB

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mern-ecommerce-project.git
   cd mern-ecommerce-project
2. **Install dependencies for backend**
   ```bash
   cd backend
   npm install

3. **Install dependencies for frontend**
    ```bash
    cd ../frontend
    npm install
    
4. **Install dependencies for admin**
   ```bash
   cd ../admin
   npm install

5.**Set up environment variables** 
Create a .env file in the backend folder and add the following:

    ```bash
    PORT=4000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret

### Technologies Used
  - Frontend: React, Redux, Axios
  - Backend: Node.js, Express, MongoDB, Mongoose
  - Admin: React, Redux, Axios
  -  Middleware: Multer (for file uploads), CORS (for handling cross-origin requests)
  -  Authentication: JWT


### License
 This project is licensed under the MIT License. See the LICENSE file for more details.

 





