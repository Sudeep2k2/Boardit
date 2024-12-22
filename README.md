# Boardit - Interactive Whiteboard Collaboration Platform

Boardit is a powerful, real-time collaboration platform that enables teams to work together on interactive whiteboards, regardless of their physical location. It's designed to foster creativity, enhance productivity, and streamline the brainstorming and planning processes for remote and distributed teams.

## Features

- Real-time collaborative whiteboarding
- User authentication and authorization
- Persistent whiteboard saving
- Multiple whiteboard support per user
- Responsive design for desktop and mobile use

## Tech Stack

- **Frontend**: React.js with Vite, Tailwind CSS
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.io
- **Authentication**: JSON Web Tokens (JWT)

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or later)
- npm (v6 or later)
- MongoDB (v4 or later)

## Installation and Setup

1. Clone the repository:
   git clone https://github.com/yourusername/boardit.git
   cd boardit

2. Install dependencies for both frontend and backend:
   cd frontend
   npm install
   cd ../backend
   npm install

3. Set up environment variables:
   Create a `.env` file in the `backend` directory with the following content:
   NODE_ENV=development
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret

   Replace `your_mongodb_connection_string` and `your_jwt_secret` with your actual MongoDB connection string and a secure random string for JWT encryption.

4. Start the backend server:
   cd backend
   npm run server

5. In a new terminal, start the frontend development server:
   cd frontend
   npm run dev

6. Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage

1. Register for a new account or log in if you already have one.
2. Once logged in, you'll be directed to your dashboard where you can create a new whiteboard or access existing ones.
3. In the whiteboard view, you can draw, add text, and collaborate in real-time with other users.
4. Your work is automatically saved, so you can always come back to it later.

Thank you for using Boardit!
