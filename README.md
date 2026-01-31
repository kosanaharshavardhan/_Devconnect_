Devconnect

Showcase your projects and get feedback with ease — a full-stack platform to help developers present their work, connect, and grow.

💡 Overview

Devconnect is a full-stack MERN-style web application designed to help developers:

Showcase projects in a portfolio-like format

Receive feedback from other developers

Connect with collaborators and peers

Manage and update profiles and project information

This repository contains both the frontend (client/) and backend (server/) code.

🚀 Features

✔ User authentication (sign up / login)

✔ Create and manage developer profiles

✔ Showcase projects with descriptions, links, and tags

✔ Leave feedback or comments

✔ Connect with other developers

✔ REST APIs for all functionality

🧱 Tech Stack

Frontend

React

HTML

CSS

JavaScript

Backend

Node.js

Express.js

Database

MongoDB (via Mongoose)

Authentication

JWT (JSON Web Tokens)

Environment Configuration

.env for secrets and environment variables

📁 Repository Structure
Devconnect/
├── client/                # Frontend React app
├── server/                # Backend Express API
├── .gitignore
└── README.md

🛠 Getting Started
Prerequisites

Make sure you have the following installed:

Node.js

npm

MongoDB (local or MongoDB Atlas)

Installation
Clone the repository
git clone https://github.com/kosanaharshavardhan/_Devconnect_.git
cd Devconnect

Install backend dependencies
cd server
npm install

Install frontend dependencies
cd ../client
npm install

⚙️ Environment Variables Setup

In the server directory, create a .env file and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

▶️ Running the Application

Open two terminals:

Terminal 1 — Backend
cd server
npm start

Terminal 2 — Frontend
cd client
npm start


The application will run on:

Frontend: http://localhost:3000

Backend: http://localhost:5000

🤝 Contributing

Contributions are welcome!

Fork the project

Create a feature branch (git checkout -b feature/foo)

Commit your changes

Push to your fork

Open a Pull Request

📄 License

This project is open-source.
