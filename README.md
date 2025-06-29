# SMART-BRIDGE-PROJECT
This is a full-stack Service Desk application designed to manage user complaints, agent assignments, and communication. The application consists of a Node.js backend API and a React-based frontend.

Features
User authentication and authorization
Complaint submission and tracking
Agent assignment and management
Real-time messaging between users and agents
Admin functionalities for overall system control
Getting Started
To set up and run the application locally, follow these steps:

Prerequisites
Node.js (LTS recommended)
npm or yarn
MongoDB (or a compatible database)
Installation
Clone the repository:

git clone <repository_url>
cd Service_Desk
Backend Setup:

Navigate to the backend directory and install dependencies:

cd backend
npm install
Create a .env file in the backend directory with your environment variables (e.g., MONGO_URI, JWT_SECRET).

Start the backend server:

npm start
Frontend Setup:

Open a new terminal, navigate to the frontend directory, and install dependencies:

cd frontend
npm install
Start the frontend development server:

npm run dev
The frontend application should now be accessible in your browser, typically at http://localhost:5173.

Technologies Used
Backend: Node.js, Express.js, Mongoose, MongoDB
Frontend: React.js, Tailwind CSS
Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.
