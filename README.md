REAL-TIME CHAT APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME: Vishal

INTERN ID: CT04DY127

DOMAIN: FULL STACK WEB DEVELOPMENT

BATCH DURATION: August 22nd, 2025 to September 22nd, 2025

MENTOR NAME: NEELA SANTHOSH KUMAR

DESCRIPTION OF TASK PERFORMED :

As part of my CODTECH internship, I developed a Real-time Chat Application using React, Node.js, Express, Socket.IO, and MongoDB. This application allows multiple users to communicate in real-time, join chat rooms, and see who is online, providing a fully interactive chat experience.

The server folder contains the Node.js backend with Express and Socket.IO for real-time messaging, MongoDB for persisting chat history, and RESTful APIs to fetch previous messages.

The client folder contains the React frontend, which provides a responsive UI, live user list, message display with timestamps, and real-time message updates via Socket.IO. React hooks (useState, useEffect, useRef) are used for state management and DOM updates.

Challenges addressed include real-time synchronization, user presence management, connection handling, and message persistence, ensuring smooth and reliable chat functionality.

This project demonstrates full-stack development, real-time application design, and API integration, offering a practical and interactive messaging solution.

OUTPUT OF THE TASK
<img width="1918" height="910" alt="image" src="https://github.com/user-attachments/assets/6170fd85-d0e7-4f5f-b13c-325568851634" />



(Replace this link with your actual screenshot)

KEY FEATURES
Server (Node.js + Express + Socket.IO)

Real-time WebSocket communication with Socket.IO

Chat history persistence with MongoDB

User presence tracking (online/offline)

Support for multiple chat rooms

RESTful API endpoints for previous messages

Client (React 18)

Real-time messaging updates

Live user list with online/offline indicators

Responsive design for desktop and mobile

Timestamped messages

Connection status display

PROJECT STRUCTURE
real-time-chat-app/
├── server/
│   ├── models/
│   │   └── Message.js
│   ├── routes/
│   │   └── messageRoutes.js
│   ├── server.js
│   └── .env
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   └── .env
└── README.md

ENVIRONMENT VARIABLES
Server .env
PORT=5000
NODE_ENV=development
MONGODB_URI=mongodb://localhost:27017/chat-app
CLIENT_URL=http://localhost:3000
DEBUG=true

Client .env
REACT_APP_SOCKET_URL=http://localhost:5000
REACT_APP_API_URL=http://localhost:5000/api


💡 For MongoDB Atlas, replace MONGODB_URI with your cloud connection string.

SETUP & INSTALLATION
1. Server Setup
cd server
npm install
# Copy the .env content above
npm start
# Or for development with auto-restart:
npm run dev

2. Client Setup
cd client
npm install
# Copy the .env content above
npm start

3. MongoDB Setup

Option A: Local MongoDB

Install MongoDB Community Server: https://www.mongodb.com/try/download/community

Start MongoDB service

Use URI: mongodb://localhost:27017/chat-app

Option B: MongoDB Atlas (Cloud)

Create a free account at https://www.mongodb.com/cloud/atlas

Create a cluster and database

Copy connection string into .env

TESTING REAL-TIME CHAT

Open http://localhost:3000 in two different browser windows.

Enter different usernames but the same room ID.

Start sending messages and observe real-time updates in both windows.

FUTURE IMPROVEMENTS

Private messaging and direct chat

Rich text formatting (emojis, images, links)

User authentication and profile pictures

Message search and filtering

Deployment to production (Heroku + Netlify + MongoDB Atlas)

AUTHOR

Developed by Vishal 🚀
