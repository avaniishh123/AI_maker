
# 🧠 AI Interview Maker

**AI Interview Maker** is a web-based application designed to help users practice job interviews with real-time AI-generated questions and instant feedback. The app also saves sessions for performance review and includes an interactive UI, 3D avatar animation, and a sentiment-based performance chart.

🎥 **[Demo Video](https://drive.google.com/file/d/18kJ0cCdflx2tUfFKjkvK7MliD-jviDP0/view?usp=sharing)**

---

## 🚀 Features

* 🎤 **Real-time AI-generated interview questions**
* 📊 **Performance feedback** using word count and sentiment analysis
* 💾 **Session storage** using REST API (`/saveSession`, `/sessions`)
* 🔁 **Real-time updates** via WebSocket (`Socket.io`)
* 👨‍💼 **Role-based questions** (Software Engineer, Product Manager, Sales Rep)
* 🎯 **Mentor Mode** for structured guidance (Context-Action-Result)
* 🧑‍🎤 **3D avatar animation** using Three.js
* 📈 **Performance visualization** with Chart.js
* 🎉 **Confetti celebration** at interview completion

---

## 🛠 Tech Stack

**Frontend:**

* HTML, CSS, JavaScript
* Three.js (3D Avatar)
* Chart.js (Performance Charts)
* Canvas Confetti
* Web Speech API

**Backend:**

* Node.js
* Express.js
* Socket.io
* REST API endpoints

---

## 📂 Project Structure

```
/ai-interview-maker
├── public/             # Frontend assets (index.html, styles, scripts)
├── node_modules/       # npm dependencies
├── server.js           # Express backend with WebSocket + REST API
├── package.json        # Project metadata and dependencies
└── package-lock.json   # Exact dependency versions
```

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/ai-interview-maker.git
cd ai-interview-maker

# Install dependencies
npm install

# Run the server
npm start
```

Access the app at: `http://localhost:3000`

---

## 📡 API Endpoints

* `POST /saveSession` – Save a completed interview session
* `GET /sessions` – Retrieve all saved sessions

---

## 📄 License

This project is licensed under the ISC License.

---
