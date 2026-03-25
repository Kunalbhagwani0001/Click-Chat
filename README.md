# 🚀 Click-Chat

> A modern **Slack-like real-time communication platform** built for teams to collaborate efficiently.

---

## 📌 Overview

**Click-Chat** is a scalable and lightweight chat application that enables seamless communication through channels and direct messages. It is designed with simplicity, performance, and usability in mind.

---

## ✨ Features

- 🔐 Secure Authentication (JWT-based)
- 💬 Real-time Messaging
- 👥 Workspace & Channel Management
- 📩 Direct Messaging (DM)
- 🟢 User Active/Inactive Status
- 🛠 Admin Controls (Add/Remove Users)
- 📂 Organized Communication Structure
- ⚡ Fast & Lightweight Performance

---

## 🏗️ Project Structure
Click-Chat/
│
├── click backend.7z # Backend source code
├── click front end.7z # Frontend source code
├── README.md # Project documentation

---

## ⚙️ Tech Stack

### Frontend
- HTML / CSS / JavaScript
- (Optional: React / Vanilla JS depending on your setup)

### Backend
- Node.js / Express.js *(assumed, update if different)*
- REST APIs

### Database
- MongoDB / SQL *(update based on your actual DB)*

### Authentication
- JWT (JSON Web Tokens)

---

## 🚀 Getting Started

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/click-chat.git
cd click-chat
``` 

### 2️⃣ Extract Files

> ⚠️ Note: These files are in `.7z` format. Use 7-Zip to extract them.

```bash
7z x "click backend.7z"
7z x "click front end.7z"
``` 

3️⃣ Setup Backend
```bash
cd backend
npm install
npm start
```

4️⃣ Setup Frontend
```bash
cd frontend
npm install
npm start
```
### 🔐 Authentication Flow

- User registers/login
- JWT token generated
- Token used for secure API requests
- Role-based access (Admin/User)
  
### 🧠 How It Works

- Users join a workspace
- Admin creates channels
- Users communicate via:
- Channels (group chat)
- Direct Messages (1-to-1)
- Admin manages users (add/remove/activate/deactivate)
