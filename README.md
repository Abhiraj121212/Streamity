Streamity - A Full-Stack Chat & Video Calling Platform
A feature-rich, full-stack communication application designed for seamless real-time messaging and high-quality video calls. Built with a modern MERN stack and integrated with the powerful Stream API, this project showcases a robust, scalable, and user-centric architecture.

Live Demo: [Link to your deployed application


✨ Key Features
This application is packed with modern features designed for an engaging user experience:

-> Real-time Messaging: Instantaneous one-on-one and group messaging with typing indicators, read receipts, and emoji reactions.

-> HD Video & Audio Calls: Crystal-clear video conferencing for both private and group conversations, powered by Stream.

-> Collaboration Tools: Includes essential features like screen sharing and call recording to enhance productivity.

-> Secure Authentication: Implements JSON Web Tokens (JWT) for secure user authentication and protected API routes.

-> Global State Management: Utilizes Zustand for efficient, minimal, and predictable state management across the React application.

-> Optimized Data Fetching: Leverages TanStack Query for simplified data fetching, caching, and synchronization, ensuring a responsive UI.

-> Highly Customizable UI: Offers 32 unique themes, allowing users to personalize their experience.

-> Comprehensive Error Handling: Robust error management on both the client and server sides to ensure a smooth user experience.

🛠️ Tech Stack & Architecture
This project is built with a modern, scalable technology stack.

Category:	Technology
Frontend:	React, TailwindCSS, TanStack Query, Zustand
Backend:	Node.js, Express.js
Database:	MongoDB
Real-time API:	Stream (for Chat & Video SDKs)
Authentication:	JSON Web Tokens (JWT)
Deployment:	[e.g., Vercel for Frontend, Render for Backend]


🚀 Getting Started
Follow these instructions to set up and run the project locally on your machine.

Prerequisites
Node.js (v18 or later)

npm / yarn / pnpm

MongoDB account

Stream account

1. Clone the Repository
Bash

git clone [your-repository-url]
cd [your-project-folder]
2. Backend Setup
Navigate to the backend directory, install dependencies, and set up your environment variables.

Bash

cd backend
npm install
Create a .env file in the /backend directory and add the following variables:

Code snippet

PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_stream_api_key
STEAM_API_SECRET=your_stream_api_secret
JWT_SECRET_KEY=your_jwt_secret_key
NODE_ENV=development
3. Frontend Setup
In a new terminal, navigate to the frontend directory, install dependencies, and set up the environment file.

Bash

cd frontend
npm install
Create a .env file in the /frontend directory and add the following:

Code snippet

VITE_STREAM_API_KEY=your_stream_api_key
4. Run the Application
You need two separate terminals to run both the backend and frontend servers concurrently.

Terminal 1: Start the Backend Server

Bash

# In the /backend directory
npm run dev
Terminal 2: Start the Frontend Development Server

Bash

# In the /frontend directory
npm run dev
Your application should now be running locally at http://localhost:5173 (or another port specified by Vite).