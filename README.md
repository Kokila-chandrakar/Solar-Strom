# 🛰️ Satellite Collision Prediction & Monitoring System

An AI-powered space safety platform built to monitor satellites, predict possible orbital collisions, and visualize space traffic in real time.

This project was developed as part of a solution challenge to improve satellite safety and reduce the risk of space debris accidents.

---

 ## 🚀 Features

* 🌍 Real-time satellite visualization using CesiumJS
* ⚠️ Collision prediction and risk analysis
* 📊 Interactive dashboard with analytics
* 🛰️ Live orbital tracking system
* 📈 Space traffic monitoring
* 🔄 Full-stack architecture with frontend and backend
* 🐳 Docker support for easy deployment

---

## 🛠️ Tech Stack

### Frontend

* React + TypeScript
* Vite
* CesiumJS
* Resium
* Recharts
* Axios

### DevOps & Tools

* Docker
* Docker Compose
* Makefile
* Git & GitHub

---
### Backend

* Python
* Flask/FastAPI (depending on implementation)
* SQLite / Database support

## 📂 Project Structure

```bash
satellite-collision-system/
│
├── frontend/          # React frontend application
├── backend/           # Backend APIs and database logic
├── docker-compose.yml
├── Makefile
├── run.sh
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/satellite-collision-system.git
cd satellite-collision-system
```

---

### 2️⃣ Install Frontend Dependencies

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

### 3️⃣ Setup Backend

```bash
cd backend
pip install -r requirements.txt
python init_db.py
```

```bash
http://localhost:5173
```

---

Run the backend server:

```bash
python app.py
```

---

## 🐳 Run with Docker

```bash
docker-compose up --build
```

---

## 📸 Screenshots

Add your project screenshots here.

```bash
/assets/dashboard.png
/assets/visualization.png
```

---

## 🎯 Problem Statement

Thousands of satellites orbit Earth every day, increasing the risk of collisions and dangerous space debris.

This system helps:

* Predict possible satellite collisions
* Improve monitoring of orbital objects
* Support safer space missions
* Provide visualization for analysis and research

---

## 🌟 Future Improvements

* AI-based collision probability scoring
* Real-time NASA/Space-Track API integration
* Alert & notification system
* Machine learning for orbital prediction
* Multi-user dashboard support

---

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Inspiration

Inspired by the growing challenge of space debris management and the need for safer satellite operations.
