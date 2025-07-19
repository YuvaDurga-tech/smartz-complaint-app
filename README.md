# 🛠️ Smartz Complaint Registration & Management System

This is a full-stack web application developed during my internship to streamline and digitize the complaint-handling process. It allows customers to register complaints, track them, and communicate with support agents in real time. Admins have complete control over complaint assignments and user management.

The platform is designed with a **role-based access model** supporting three users:
- **Customer (User)** – Registers and tracks complaints
- **Agent** – Resolves and updates complaint statuses
- **Admin** – Manages users, agents, and complaints centrally

---

## 🌟 Key Features

### 👤 Users
- Register and log in securely
- Submit complaints with details (name, address, city, pincode, description)
- Track complaint status in real-time (Pending → In-Progress → Resolved)
- Chat with assigned agents
- Manage personal profile

### 👨‍💼 Agents
- Log in to view assigned complaints
- Update complaint status and progress
- Communicate with users through built-in messaging
- View complaint history

### 👩‍💼 Admin
- Manage all registered users and agents
- Assign complaints to agents
- Oversee complaint resolution and progress dashboard
- Full control panel to manage platform operations

---

## 💻 Tech Stack

| Layer         | Technologies Used                          |
|---------------|--------------------------------------------|
| **Frontend**  | React.js, HTML, CSS, Bootstrap, Material UI |
| **Backend**   | Node.js, Express.js, MongoDB, Mongoose     |
| **Auth**      | JSON Web Tokens (JWT)                      |
| **Real-time** | Socket.io (for chat system)                |
| **Database**  | MongoDB (Cloud or Local)                   |

---

## 🧠 System Architecture

This app follows a **client-server architecture**.

- The **Frontend** (React) uses Axios to call APIs and manage state.
- The **Backend** (Node/Express) handles all APIs, JWT-based authentication, and MongoDB interactions.
- Socket.io enables real-time chat between users and agents.
- The database includes multiple schemas: Users, Complaints, Assigned Complaints, and Messages.

---

## 🗂️ Folder Structure

smartz-complaint-app/
├── Project files/
│ ├── Frontend/ # React frontend
│ └── Backend/ # Node + Express backend
├── Document/ # Final report, screenshots
├── Video doc/ # Demo video or video_link.txt
└── README.md # This file

---

## 🚀 Setup Instructions

### 🔧 Prerequisites
- Node.js and npm installed
- MongoDB database (local or Atlas)
- VS Code or any code editor

---

### 📦 
1. Clone the Project

```bash
git clone https://github.com/YuvaDurga-tech/smartz-complaint-app.git
cd smartz-complaint-app

 2. Setup Backend
bash
Copy code
cd "Project files/Backend"
npm install
Create a .env file in the backend folder:

ini
Copy code
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Start the backend server:

bash
Copy code
node index.js
Runs at: http://localhost:8000

💻 3. Setup Frontend
bash
Copy code
cd ../Frontend
npm install
npm start
Runs at: http://localhost:3000


🎥 Project Demo
📽️ Click here to watch the project demo
https://drive.google.com/file/d/1zrSw_kLbT1QkPj5bYYnEgrVTWlfYf_8r/view?usp=sharing

Also available in Video doc/video_link.txt

🧑‍🎓 Submitted By
Yuva Durga
B.Tech – [CSE-Cyber Security]
Internship Project – 2025
GitHub: YuvaDurga-tech







