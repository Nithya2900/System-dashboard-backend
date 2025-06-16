# 🖥️ System Dashboard Backend

This is the backend service for the **System Dashboard** — a real-time system monitoring application that fetches live statistics about CPU usage, memory, disk space, and operating system details using Node.js and the `systeminformation` library.

## 🚀 Features

- 🔄 Real-time system metrics
- 🧠 CPU details including usage and temperature
- 📦 Memory statistics (total, free, used)
- 💽 Disk space analysis
- 💻 OS and hardware information
- 🌐 CORS-enabled API for frontend integration

## 🛠️ Technologies Used

- **Node.js**
- **Express.js**
- **systeminformation** – For system metrics
- **CORS** – To enable cross-origin requests

**🧪 How to Run Locally** 
Clone the repository:

```bash
git clone https://github.com/Nithya2900/System-dashboard-backend.git
cd System-dashboard-backend

Install dependencies: 
npm install

Start the server:
node server.js

Visit:
http://localhost:5000/api/stats
```
🌐 Deployment
The backend is live on Render.
https://system-dashboard-backend-wl6q.onrender.com

