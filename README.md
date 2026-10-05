# 💬 Real-Time Chat Application

A full-stack real-time chat application built using React, Node.js, Express, MongoDB, Socket.IO and Cloudinary.

## 🚀 Live Demo

🔗 https://chat-application-project-1.onrender.com

## 📌 About The Project

This project is a full-stack web-based chat application designed for real-time communication between users.

The application uses a React frontend and a Node.js/Express backend. MongoDB is used for data storage, Socket.IO enables real-time communication, and Cloudinary is used for cloud-based image storage.

## ✨ Features

- 🔐 User Registration and Login
- 🔑 JWT-based Authentication
- 💬 Real-time Messaging
- ⚡ Real-time communication using Socket.IO
- 👤 User Management
- 🖼️ Image Upload and Sharing
- ☁️ Cloudinary Media Storage
- 🗄️ MongoDB Database
- 📱 Responsive User Interface
- 🔒 Protected API Routes
- 🚀 Deployment using Render

## 🛠️ Tech Stack

### Frontend

- React.js
- JavaScript
- HTML5
- CSS3
- Vite

### Backend

- Node.js
- Express.js
- Socket.IO
- JWT
- Mongoose

### Database

- MongoDB

### Cloud Services

- Cloudinary
- Render

## 🏗️ Project Architecture

```text
                    ┌─────────────────────┐
                    │        User         │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   React Frontend    │
                    │       (Vite)        │
                    └──────────┬──────────┘
                               │
                     HTTP / REST API
                         + Socket.IO
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Node.js + Express  │
                    │      Backend        │
                    └──────┬───────┬──────┘
                           │       │
                  ┌────────▼───┐   │
                  │  MongoDB   │   │
                  └────────────┘   │
                                   ▼
                            ┌────────────┐
                            │ Cloudinary │
                            └────────────┘

## 📂 Project Structure

```text
Chat-application-project/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── package.json
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── .gitignore
├── package.json
└── README.md


**2. ⚙️ Installation**

Explain how someone can clone and install the project.

**3. 🔐 Environment Variables**

Document the required variable **names only**. Never put your actual secrets in README.

**4. ▶️ Run Locally**

Show:

```bash
cd backend
npm start

## 🚀 Live Demo

https://chat-application-project-ktpt.onrender.com

