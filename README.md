# GearGuard – Maintenance Management Dashboard (MERN)

🚀 GearGuard – Smart Maintenance Management System (MERN)

GearGuard is a full‑stack MERN application designed to simplify and digitize industrial equipment maintenance workflows. Built with scalability and real‑world usability in mind, it provides centralized control over equipment, maintenance requests, and technician teams through Kanban boards and calendar‑based planning.

This project is crafted as a hackathon‑ready, portfolio‑grade solution, ideal for platforms like Odoo Hackathon / Smart Industry challenges.


---

🌟 Problem Statement

Industries often struggle with:

Scattered maintenance records

Missed or delayed service requests

Poor visibility of equipment lifecycle

Lack of ownership among maintenance teams


GearGuard addresses these challenges by offering a unified, visual, and structured maintenance management platform.


---

✨ Key Features

🏭 Equipment Management

Create, update, delete, and list equipment

Track equipment lifecycle: Active → Under Maintenance → Scrap

Maintain critical metadata for better decision‑making


🛠 Maintenance Requests (Kanban Workflow)

Visual Kanban board with stages:

New

In Progress

Completed

Scrap


Status updates with intuitive UI interactions

Clear visibility of pending vs completed work


📅 Maintenance Calendar

Calendar view for upcoming and past maintenance tasks

Quickly identify:

Overloaded days

Overdue maintenance

Scheduling gaps



👥 Team Management

Create and manage maintenance teams

Assign requests and equipment to teams

Improves accountability and task ownership


🧩 Clean & Scalable Architecture

Clear separation of frontend and backend

Modular folder structure for easy scaling

Domain‑driven controllers, models, and routes



---

🧱 Tech Stack

Frontend

React.js (SPA)

Modular components for Dashboard, Equipment, Requests, and Teams

Custom CSS for Kanban, Calendar, and responsive UI


Backend

Node.js + Express.js

RESTful API design

Centralized error‑handling middleware


Database

MongoDB with Mongoose

Models:

Equipment

MaintenanceRequest

MaintenanceTeam



Tooling & Utilities

Axios (API communication)

dotenv (environment variables)

nodemon (development workflow)



---

📁 Project Structure

Gearguard-MERN/
├── client/                 # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       ├── styles/
│       └── App.jsx
├── server/                 # Express Backend
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── .gitignore
└── README.md


---

🚀 Getting Started (Local Setup)

1️⃣ Clone the Repository

git clone https://github.com/divyeshgangara2211/Gearguard-MERN.git
cd Gearguard-MERN

2️⃣ Backend Setup

cd server
npm install

Create a .env file inside server:

MONGO_URI=your_mongodb_connection_string
PORT=5000

Run backend:

npm run dev

Backend runs on:

http://localhost:5000


---

3️⃣ Frontend Setup

cd client
npm install
npm start

Frontend runs on:

http://localhost:3000


---

🔌 API Overview

Equipment APIs

GET    /api/equipment

POST   /api/equipment

PUT    /api/equipment/:id

DELETE /api/equipment/:id


Maintenance Request APIs

GET    /api/requests

POST   /api/requests

PUT    /api/requests/:id


Team APIs

GET    /api/teams

POST   /api/teams

PUT    /api/teams/:id


All API calls are managed through a centralized Axios service layer in the frontend.


---

🧠 What This Project Demonstrates

Real‑world MERN stack architecture

Full CRUD flows (Database ↔ API ↔ UI)

REST API best practices

State‑driven UI (Kanban & Calendar)

Production‑ready environment handling


This project is highly suitable for:

Hackathons (Odoo / Smart India / Industry 4.0)

MERN Stack Internships & Fresher Roles

Portfolio & Resume Showcase



---

🚧 Future Enhancements

Authentication & Role‑based access (Admin / Technician)

Advanced filtering & search

Analytics dashboard (MTTR, downtime, trends)

File uploads for reports & manuals

Cloud deployment (Vercel / Render / Railway)



---

🤝 Contributing & Feedback

This is a learning‑driven and innovation‑focused project.

Contributions, feedback, and feature ideas are welcome — especially those that push GearGuard closer to a production‑grade CMMS solution.


---

✨ Built with the vision of making maintenance smarter, visual, and reliable.

---
