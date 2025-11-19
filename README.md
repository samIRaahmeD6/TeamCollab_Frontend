TeamCollab – Real-Time Messaging and Task management app

A real-time collaboration and messaging platform built with Node.js, Express, Socket.IO, MySQL, and React (Vite).
Backend is deployed on Namecheap, and the frontend is hosted on GitHub Pages.

🚀 Live Demo

![Demo](./client/src/assets/teamcollab.gif)
🔗 Frontend (GitHub Pages):

[https://samiraahmed6.github.io/TeamCollab_Frontend/](https://samiraahmed6.github.io/TeamCollab_Frontend/)

🔗 Backend API (Namecheap):

[https://hasibul-rupok.com/teamCollab/api/](https://hasibul-rupok.com/teamCollab/)

📌 Features
✅ User System

User registration

User login

Plain text password comparison (no bcrypt)

💬 Real-Time Messaging


Group chat

Online users sidebar

Task assignment and Drag and Drop option

Real-time WebSocket communication using Socket.IO

📁 Database Stored in MySQL

Users

Messages

Tasks


🖥 Frontend (React + Vite + Tailwind CSS)

Login & Register pages

Sidebar with user list

Chat UI

Task Assignment with Drag and Drop option

🏗 Tech Stack
Frontend

React (Vite)

Tailwind CSS

Socket.IO Client

GitHub Pages Deployment

Backend

Node.js

Express.js

MySQL

Socket.IO

Hosted on Namecheap Shared Hosting

📂 Project Structure
TeamCollab/
│── client/                # React frontend
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
│── server/                # Node.js backend
│   ├── routes/
│   ├── controllers/
│   ├── database/
│   └── server.js

🔧 Environment Variables (Backend)

Create .env in the backend folder:

DB_HOST=localhost
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=teamcollab

🌐 Deployment Details


✔ Backend – Namecheap Shared Hosting

Backend deployed using:

Node.js App Manager

MySQL Database

Custom API route:[
https://hasibul-rupok/teamCollab/api/
](https://hasibul-rupok.com/teamCollab/api)

✔ Frontend – GitHub Pages Deployment


export default defineConfig({
  base: '/TeamCollab_Frontend/',
});


Add GitHub workflow or manually deploy using:

npm run build
git subtree push --prefix dist origin gh-pages

⚙ Running Locally
Backend
cd server
npm install
npm start

Frontend
cd client
npm install
npm run dev

🧪 API Endpoints
🔹 Authentication
Method	Endpoint	Description
POST	/api/register Register user
POST	/api/login	Login user
🔹 Users
Method	Endpoint	Description
GET	/api/user	Get list of users


🧑‍💻 Author

Samira Ahmed
Full Stack Developer

GitHub: https://github.com/samiraahmed6
