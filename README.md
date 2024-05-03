# Quality_Management

This project is an E-commerce Management System built using React for the front end, Redux for state management, and Axios for handling HTTP requests. It allows users to register, login, manage product quality, view product qualty details, and update their profiles.

# Introduction

The E-Commerce Management System is a web application designed to provide users with a platform to manage their online store efficiently. Users can register and log in to their accounts, add, edit, and delete products quality, view product quality details, update their profiles, and more.

# Features

- User authentication: Users can register, login, and logout securely.
- Product quality management: Users can add, edit, and delete products quality from their inventory.
- Product quality details: Users can view detailed information about each product.
- Profile management: Users can update their profile information, including name, email, phone, and bio.
- Password management: Users can change their passwords for added security.
- Responsive design: The application is responsive and works well on desktops, tablets, and mobile devices.

# Technologies Used

- React: Frontend JavaScript library for building user interfaces.
- Redux: State management library for managing application state.
- React Router: Library for routing in React applications.
- Axios: Promise-based HTTP client for making HTTP requests.
- React Toastify: Notification library for displaying toast messages.
- Cloudinary: Cloud-based image and video management service for image upload.
- Express.js: Minimalist web framework for Node.js used in the backend.
- MongoDB: NoSQL database used for storing user and product data.
- Mongoose: MongoDB object modeling library for Node.js used for database interaction.

# Getting Started with Project

To get started with the project, follow these steps:

1. Clone the Repository: Clone the project repository to your local machine using the following command:
    - git clone <repository_url> 
2. Install Dependencies: Open a terminal within the project directory and run the following command to install all dependencies:
    - npm install 
3. Create .env file: use "MONGO" for your MongoDB url and use "JWT_SECRET" for secret key:
    - JWT_SECRET = "anything"
    - MONGO = "mongodb+srv://xxx:xxx@xxx-xxx.nfsmyma.mongodb.net/?retryWrites=true&w=majority&appName=xxx-xxx"
4. Run Backend Server: Start the backend server by running the following command in the terminal:
    - npm run dev
5. Run Frontend Server: Open a new terminal and navigate to the frontend directory within the project directory using the following command:
    - cd frontend
6. Create .env file: use "VITE_FIREBASE_API_KEY" for your firebase api key:
    - VITE_FIREBASE_API_KEY  = ""AIzaxxxxxxxxxxxxxxxxxxx"
7. Then, run the following command to start the frontend server:
    - npm run dev
8. Access the Application: Open a web browser and go:
    -  http://localhost:5173/
9. Login: You can log in as an admin, faculty, or student using the provided credentials.
10. With these steps, you should now be able to run the project locally and access it through your web browser.

# Usage
- Register or login to your account.
- Add, edit, or delete products quality from your inventory.
- View detailed information about each product.
- Update your profile information.
- Change your password for added security.
