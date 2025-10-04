# 📹 Video Call Application

A real-time video calling application built with **Next.js** (frontend) and **Node.js/Express** (backend), designed to provide seamless peer-to-peer communication.

---

## 🚀 Features

* 🔐 User authentication (login/signup)
* 🎥 One-to-one video calling
* 👥 Group calls support (optional)
* 💬 Real-time chat during calls
* 📡 WebRTC integration for media streaming
* ⚡ Socket.io signaling server for connections
* 🎨 Responsive UI with Tailwind CSS

---

## 🛠️ Tech Stack

**Frontend:**

* Next.js
* React
* Tailwind CSS
* Socket.io Client

**Backend:**

* Node.js + Express
* Socket.io
* MongoDB (for user & call session data)

---

## 📂 Project Structure

```
video-call/
│── backend/        # Express server, socket logic
│── frontend/       # Next.js app
│── Zoom/           # Zoom clone components (added module)
│── package.json    # Dependencies
│── README.md       # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/honey610/video-call.git
cd video-call
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup environment variables

Create a `.env` file in the root:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NEXT_PUBLIC_SOCKET_URL=http://localhost:5000
```

### 4️⃣ Run backend server

```bash
cd backend
npm start
```

### 5️⃣ Run frontend (Next.js)

```bash
cd frontend
npm run dev
```

Now open 👉 `http://localhost:3000` in your browser.

---

## 📸 Screenshots (Optional)

*Add screenshots or GIFs here to showcase the app UI and functionality.*

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repo
* Create a new branch (`feature-xyz`)
* Commit changes and open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.
Feel free to use and modify it for your own projects.

---
