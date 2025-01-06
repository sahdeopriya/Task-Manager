
# Task Manager

Task Manager is a robust and feature-rich task management application built using the MERN stack (MongoDB, Express.js, React, and Node.js). This application is designed to streamline task organization and improve productivity by allowing users to create, view, update, and delete tasks seamlessly.

The project offers a clean, responsive, and intuitive user interface powered by React and styled with Tailwind CSS. On the backend, Node.js and Express.js ensure secure and efficient API handling, while MongoDB provides a scalable and flexible database solution.

Key highlights include secure user authentication, real-time notifications, and a dynamic dashboard, making this application ideal for both users seeking an effective task management solution and developers looking to explore modern web development practices.

## ✨Core Features

### For Users
User Authentication: Register, login, and logout securely
Task Management: Add, view, update, and delete tasks
Seamless Navigation with a dynamic dashboard
### For Developers
Toast notifications for feedback (success/error)
Full-stack form validation (frontend & backend)
Token-based Authentication (JWT)
Global state management with Redux
Dynamic page titles and redirects
Reusable components (e.g., layout, loaders)
Custom hooks (e.g., useFetch) for streamlined coding
Middleware for backend request validation
Tailwind CSS for a lightweight, custom-styled UI


## Screenshots

![App Screenshot](https://res.cloudinary.com/dgjihp0pq/image/upload/v1735979124/Screenshot_2025-01-04_134557_ersxso.png)

![App Screenshot](https://res.cloudinary.com/dgjihp0pq/image/upload/v1735979118/Screenshot_2025-01-04_134610_koug0z.png)

![App Screenshot](https://res.cloudinary.com/dgjihp0pq/image/upload/v1735979117/Screenshot_2025-01-04_134627_yqi9b6.png)

![App Screenshot](https://res.cloudinary.com/dgjihp0pq/image/upload/v1735979127/Screenshot_2025-01-04_134658_erqobv.png)

![App Screenshot](https://res.cloudinary.com/dgjihp0pq/image/upload/v1735979120/Screenshot_2025-01-04_134713_bqxyoc.png)

![App Screenshot](https://res.cloudinary.com/dgjihp0pq/image/upload/v1735979128/Screenshot_2025-01-04_134738_gzepan.png)

![App Screenshot](https://res.cloudinary.com/dgjihp0pq/image/upload/v1735979121/Screenshot_2025-01-04_134800_vj1qry.png)


## 🛠️ Tech Stack

Frontend: React, Redux, Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB
## 📦 Key Dependencies

axios, redux-thunk - For API interactions and asynchronous actions
jsonwebtoken, bcrypt - For authentication and password security
mongoose - For database schema and operations
react-toastify - For interactive user notifications
## 🔧 Development Tools

nodemon - Automatically restarts the server on file changes
concurrently - Runs multiple processes simultaneously
## ⚙️ System Setup

1. Ensure you have Node.js installed on your machine.
2. Set up a MongoDB database (local or cloud-based).
3. Install a code editor like Visual Studio Code.
## 🚀 Getting Started

1. Clone the Repository
 
```bash
  git clone https://github.com/aayush301/MERN-task-manager.git  
  cd MERN-task-manager  
```
2. Install Dependencies
```bash
  npm run install-all   
```
3. Configure Environment Variables
Create a .env file in the backend directory and populate it using the .env.example template.

4. Run the Application for Backend
```bash
  npm run dev    
```

5. Run the Application for Frontend
```bash
  npm start
```

Visit http://localhost:3000 in your browser.
## 📡 API Documentation

### Authentication
POST /api/auth/signup - Register a new user
POST /api/auth/login - Log in with existing credentials

### Task Operations
GET /api/tasks - Fetch all tasks
GET /api/tasks/:taskId - Fetch details of a specific task
POST /api/tasks - Add a new task
PUT /api/tasks/:taskId - Update an existing task
DELETE /api/tasks/:taskId - Remove a task

### Profile
GET /api/profile - Retrieve user details
## 🌐 Frontend Routes

/ - Dashboard (for authenticated users) or landing page (for guests)

/signup - User registration

/login - User login

/tasks/add - Add a new task

/tasks/:taskId - Edit an existing task
## 📜 Scripts

### Root-Level Scripts
npm run dev - Launch backend and frontend concurrently
npm run dev-server - Start backend only
npm run dev-client - Start frontend only
npm run install-all - Install all project dependencies

### Frontend-Specific Scripts
npm start - Launch the frontend in development mode
npm run build - Compile the frontend for production
npm test - Run tests in interactive watch mode

### Backend-Specific Scripts
npm run dev - Start the backend server with live reload (nodemon)
npm start - Start the backend without live reload
## 🔗 Helpful Links

### Documentation
React.js
MongoDB
npm

### Tutorials
Express.js Guide
React Crash Course
Redux Basics

### Tools and Cheatsheets
Node.js Download
VS Code
Git Cheat Sheet
## 📬 Reach Out

For questions or feedback, contact:

Email: priyasahdeo706@gmail.com
