AI INTERVIEW MAKER

AI Interview Maker is a web-based application designed to help users practice and analyze interview responses. It provides real-time AI-generated interview questions and stores user responses for later review. The backend is powered by Node.js & Express.js, and it uses WebSockets (Socket.io) for real-time communication.

i) Features
1. Real-time AI-generated interview questions – Users receive dynamically generated questions.
2. Session storage with REST API – Save interview sessions for later review.
3. WebSocket-based real-time updates – Ensures instant feedback and interaction.
4. Simple UI for seamless user experience – Minimalistic, easy-to-use frontend.

ii) How it works
1. User accesses the application via the frontend (index.html).
2. AI-generated questions appear dynamically.
3. User answers the questions, and data is sent to the backend (/saveSession).
4. Data is stored and can be retrieved via GET /sessions.
5. WebSocket (socket.io) updates all connected clients with new sessions in real time.


iii) Project structure

/ai-interview-maker
│── public/             # Frontend files (index.html, styles, scripts)
│── node_modules/       # Installed dependencies
│── server.js           # Express.js backend with REST API and WebSockets
│── package.json        # Project dependencies and scripts
│── package-lock.json   # Lockfile for npm dependencies
│── README.md           # Documentation
