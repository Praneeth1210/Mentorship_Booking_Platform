🎓 Mentorship Booking Platform
A full-stack web application that connects students with faculty mentors through a seamless system of profile discovery, session booking, real-time communication, and secure payments.
This platform aims to digitize mentorship in academic institutions, allowing students to book 1:1 sessions with faculty based on skills, availability, and subject expertise — while enabling mentors to manage their schedules and interact with students effectively.

✨ Key Highlights
🔐 JWT Authentication with role-based access (Student / Faculty)
📅 Mentorship Session Booking with real-time availability
💬 Live Chat system built using Socket.io
💳 Secure Payment Integration with Stripe
📚 Detailed Faculty Profiles with filtering by subject, skills, and counseling availability
📈 Dashboards for both students and faculty to track sessions and profile updates
⚙️ Robust RESTful APIs for full backend interaction

🛠️ Tech Stack
Frontend
React.js – UI library for component-driven design
React Router DOM – Handles navigation and routing
Redux / React-Redux – Global state management
Material UI (MUI) – Beautiful, responsive components
Axios – API request handling
React Hook Form – Form validation and management
React Toastify – Alert and notification system
Socket.io Client – Real-time communication with backend

Backend
Node.js + Express.js – REST API and business logic
MongoDB + Mongoose – NoSQL database for structured document storage
JWT (jsonwebtoken) – Token-based authentication
Bcrypt.js – Password hashing and comparison
Socket.io – Real-time bi-directional communication (chat)
Stripe API – Payment processing and session monetization
Multer – File upload middleware
Dotenv, CORS, Body-Parser – Middleware utilities

📦 Features by Role
👨‍🎓 Student
Register and log in securely
Browse mentors by subject, skill, or availability
Book sessions with preferred faculty
Make secure payments for sessions
Chat with faculty in real-time after booking
View and manage all booking history

👩‍🏫 Faculty
Register and set up a public profile
Add subjects, skills, hourly rates, availability
View incoming session requests
Accept or reject bookings
Communicate with students in real-time
Manage session history and payment status

⚙️ Local Development Setup
Prerequisites
Node.js & npm installed
MongoDB installed or cloud URI
Git installed

🚧 Future Enhancements
WebSocket-based notifications for chat and booking updates
Admin dashboard for platform moderation
Rating and review system for faculty
Google Calendar integration for automatic schedule sync
Email/SMS notifications
Mobile version (React Native)

⚙️ Backend Setup
1. Initialize and Install Dependencies
Start by initializing a new Node.js project and installing the required dependencies:
npm init -y
npm install express mongoose jsonwebtoken bcryptjs cors dotenv socket.io multer body-parser

2. Create a .env File
Set up your environment variables in a .env file:
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
PORT=5000

3. Start the Server
Once your environment is set, start the backend server:
node server.js

🌐 Frontend Setup
1. Navigate to the Frontend Directory
Change to the frontend directory:
cd frontend

2. Install Frontend Dependencies
Install the necessary frontend libraries to get started:
npm install react react-dom react-router-dom axios redux react-redux @mui/material @emotion/react @emotion/styled react-hook-form react-icons socket.io-client react-toastify next

3. Create a .env File for Frontend
Create a .env file for your frontend configuration:
REACT_APP_API_URL=http://localhost:5000/api

4. Start the Development Server
Run the frontend development server:
npm start

With these steps completed, both the frontend and backend of the Mentorship Booking Platform will be fully set up and running on your local machine!
