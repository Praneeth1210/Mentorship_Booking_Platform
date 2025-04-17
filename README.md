🎓 Mentorship Booking Platform
A full-stack web application that connects students with faculty mentors through a seamless system of profile discovery, session booking, real-time communication, and secure payments.
This platform aims to digitize mentorship in academic institutions, allowing students to book 1:1 sessions with faculty based on skills, availability, and subject expertise — while enabling mentors to manage their schedules and interact with students effectively.

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
