Devconnect

Showcase your projects and get feedback with ease — a full-stack platform to help developers present their work, connect, and grow.

💡 Overview

Devconnect is a full-stack MERN-style web application designed to let developers:

Showcase projects in a portfolio-like format

Receive feedback from others

Connect with developers or collaborators

Manage and update profile and project info

This repository contains both the frontend (client/) and backend (server/) code.

🚀 Features

✔ User authentication (sign up / login)
✔ Create and manage your developer profile
✔ Showcase projects with descriptions, links, and tags
✔ Leave feedback or comments
✔ Connect with other developers
✔ REST APIs for all functionality

🧱 Tech Stack

Frontend: React, HTML, CSS, JavaScript

Backend: Node.js, Express.js

Database: MongoDB (via Mongoose)

Authentication: JWT (JSON Web Tokens)

Environment: .env config for secrets

📁 Repo Structure
_Devconnect_/
├── client/                # Frontend React app
├── server/                # Backend Express API
├── .gitignore
└── README.md

🛠 Getting Started
Prerequisites

Make sure you have installed:

Node.js

npm

MongoDB (local or Atlas)

Installation

Clone the repo

git clone https://github.com/kosanaharshavardhan/_Devconnect_.git
cd _Devconnect_


Install backend dependencies

cd server
npm install


Install frontend dependencies

cd ../client
npm install

⚙️ Setup Environment Variables

In the server directory, create a .env file like:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

🏃 Running the App

Open two terminals:

Terminal 1 — Backend

cd server
npm start


Terminal 2 — Frontend

cd client
npm start


The React app should start (e.g., at http://localhost:3000
) and the API at http://localhost:5000
.

🤝 Contributing

Contributions are welcome! Here’s how to help:

Fork the project

Create a feature branch (git checkout -b feature/foo)

Commit your changes

Push to your fork

Open a Pull Request

📄 License

This project is open-source
