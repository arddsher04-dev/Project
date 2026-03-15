🎓 EduStream - MERN Stack E-Learning Platform
EduStream is a high-performance, full-stack E-learning platform designed to bridge the gap between instructors and students. Built using the MERN Stack, it provides a seamless interface for course discovery and student enrollment.

🚀 Key Features
User Authentication: Secure Login/Signup system with role-based identity management.

Dynamic Course Catalog: Real-time fetching of professional courses with category filtering.

Enrollment System: One-click enrollment logic connecting students to specific course IDs.

Role-Based UI: Dynamic Navbar and page views that adapt based on whether the user is a Student or Instructor.

Database Relationships: Advanced Mongoose modeling using references (ObjectId) to link Users, Courses, and Enrollments.

Responsive Design: Fully mobile-responsive interface built with Bootstrap 5 and modern CSS transitions.

🛠️ Tech Stack
Frontend:

React.js: Functional components, Hooks (useState, useEffect), and Context API logic.

Axios: For handling asynchronous HTTP requests to the backend.

Bootstrap 5: Modern UI components and grid system.

React Router Dom: Client-side routing and navigation.

Backend:

Node.js & Express.js: Scalable server-side architecture and RESTful API endpoints.

MongoDB & Mongoose: NoSQL database for flexible data storage and structured schema modeling.

📂 Project Structure
Plaintext
├── client/                # React Frontend
│   ├── src/
│   │   ├── components/    # Reusable UI (Navbar, CourseCard, LoadingSpinner)
│   │   ├── pages/         # View components (Home, Courses, Login, StudentDashboard)
│   │   └── App.js         # Routing and Global State
├── server/                # Express Backend
│   ├── models/            # Mongoose Schemas (User, Course, Enrollment)
│   ├── routes/            # API Endpoints (Auth, Course Management, Student Actions)
│   └── server.js          # Entry point and Middleware configuration

📊 Database Architecture
The project implements a relational-style NoSQL design:

User Model: Handles names, emails, hashed passwords, and roles (Student, Instructor).

Course Model: Contains course metadata, pricing, and a reference to the Instructor ID.

Enrollment Model: A bridge table tracking the Student ID, Course ID, and student Progress.

Backend Configuration:

Bash
cd server
npm install
# Create a .env file and add:
# MONGO_URI=your_mongodb_connection_string
# PORT=5000
npm start
Frontend Configuration:

Bash
cd client
npm install
npm start

📝 License
This project was developed for educational purposes as part of a Web Development course.

📝 Student Declaration
I confirm that this project is my own work and has been developed as part of the MERN Stack Web Development Final Assessment.

Name: Ardd Sher Azhar

Date: 15 March 2026
