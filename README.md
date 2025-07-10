# MAN-SPACE-PROJECT# 🧠 ManSpace – A Safe Anonymous Support Platform for Men

> A MERN stack application where men can share what they’re going through anonymously and receive supportive replies or possible solutions from others.

---

## 🚀 Live Demo
Coming soon...

---

## 🎯 Purpose

Men go through a lot in silence. *ManSpace* is a digital support platform created to give men a safe, judgment-free space where they can:
- Share their thoughts and struggles anonymously
- Get advice, emotional support, or encouragement
- Connect without the fear of being judged or identified

---

## 🛠 Tech Stack

*Frontend:* React, Axios, Tailwind CSS (optional)  
*Backend:* Node.js, Express  
*Database:* MongoDB with Mongoose  
*Others:* CORS, dotenv, Nodemon (for dev)

---

## 🔐 Key Features

- Anonymous posting (no login required)
- Supportive replies to each post
- Zero user identity stored
- Optional: categories (e.g., relationships, mental health)
- Optional: AI-generated positive responses or moderation

---

## 📁 Folder Structure

manspace/
├── backend/
│   ├── controllers/
│   │   ├── postController.js
│   │   └── replyController.js
│   ├── models/
│   │   ├── Post.js
│   │   └── Reply.js
│   ├── routes/
│   │   ├── postRoutes.js
│   │   └── replyRoutes.js
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── PostForm.jsx
│   │   │   ├── PostList.jsx
│   │   │   └── ReplySection.jsx
│   │   ├── pages/
│   │   │   └── PostPage.jsx
│   │   ├── api.js
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│
├── README.md
└── LICENSE


---

## ⚙ Installation & Setup

### 1. Clone the repo
```bash
git clone https://github.com/nem74/manspace.git
cd manspace

###  2. backend setup
cd backend
npm install
cp .env.example .env  # Add your MongoDB URI and PORT
npm run dev

###  3. frontend setup
cd ../frontend
npm install
npm start