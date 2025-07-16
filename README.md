# Complaint Registration & Management System

This is a full-stack web application developed as part of my internship project. The system helps users register complaints, allows agents to manage complaints, and provides admin with full control of the platform.

## 🔥 Features
- User Signup and Login
- Submit complaints with name, address, city, pincode, and description
- Track complaint status (Pending, In-Progress, Resolved)
- Admin assigns complaints to agents
- Agents update status
- Real-time messaging per complaint
- Admin manages users
- Complaint dashboard

## 💻 Tech Stack Used

### 🚀 Frontend
- React.js
- HTML & CSS
- JavaScript
- Bootstrap / Material UI

### 🛠️ Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT

## 📁 Folder Structure
```
smartz-complaint-app/
│
├── backend/
│   ├── index.js
│   ├── Schema.js
│   ├── config.js
│   ├── .env
│   ├── package.json
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── .gitignore
│
└── README.md
```

## ⚙️ Setup Instructions

### 🔧 Prerequisites:
- Node.js and npm installed
- MongoDB database (you can use MongoDB Atlas)

### 🚀 Steps to Run the Project:

#### 1. Clone the repository
```bash
git clone https://github.com/YuvaDurga-tech/smartz-complaint-app.git
cd smartz-complaint-app
```

#### 2. Setup Backend
```bash
cd backend
npm install
```

✅ Create a `.env` file in `/backend` folder with:
```env
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Then run:
```bash
node index.js
```

#### 3. Setup Frontend
```bash
cd ../frontend
npm install
npm start
```

Frontend runs on: `http://localhost:3000`  
Backend runs on: `http://localhost:8000`


# 🎬 Project Demo
Watch the full demo video here:  
👉 [Click to view on Google Drive](https://drive.google.com/file/d/1Lp9wGMNe4QFYirs5CWIHOLWF0CwXee0d/view?usp=sharing)

---



