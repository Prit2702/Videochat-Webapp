# 📹 Videochat-Webapp

A **browser-based real-time communication platform** supporting video/audio calls, chat, and screen sharing. Built with **WebRTC**, **Socket.IO**, **React.js**, and **Node.js**, it offers fast, secure, and scalable conferencing without relying on heavy servers for media transmission.

---

## 🚀 Features

* **Real-Time Video & Audio Calls** – Peer-to-peer streaming using WebRTC for minimal latency.
* **Screen Sharing** – Share your screen with other participants in one click.
* **Instant Room Creation** – Unique meeting rooms generated instantly without sign-up.
* **Live Chat** – Real-time text messaging alongside video conferencing.
* **Responsive UI** – Adaptive layouts built with Material-UI and Ant Design for all devices.
* **Scalable Deployment** – Optimized to handle multiple concurrent rooms with minimal server bandwidth usage.

---

## 🛠 Tech Stack

**Frontend:**

* React.js
* Material-UI / Ant Design

**Backend:**

* Node.js
* Express.js
* Socket.IO

**Real-Time Communication:**

* WebRTC

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/video-conferencing-platform.git
cd video-conferencing-platform
```

### 2️⃣ Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd ../client
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the **server** directory:

```env
PORT=5000
```

### 4️⃣ Start the Application

Run Backend:

```bash
cd server
npm start
```

Run Frontend:

```bash
cd ../client
npm start
```

---

## 📷 Screenshots

*(Add screenshots of your UI here for better presentation)*

---

## 📈 How It Works

1. **Room Creation** – A user creates a meeting room.
2. **Signaling** – Socket.IO handles participant connection and exchange of WebRTC offer/answer & ICE candidates.
3. **Peer-to-Peer Streaming** – WebRTC establishes a direct connection for audio/video.
4. **UI Rendering** – Dynamic video grids adjust automatically as participants join/leave.

---

## 📌 Future Enhancements

* Recording meetings
* Authentication & user profiles
* File sharing during calls
* Virtual backgrounds

---

## 📜 License

This project is licensed under the MIT License.