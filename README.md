#🚚 SmartRoute – Optimized Delivery Routing & Time Prediction System

<p align="center">
  <img src="https://github.com/Vijay2101/SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction/blob/main/images/Screenshot%20from%202025-01-28%2011-25-18.png?raw=true" width="750"/>
</p>

---

## 🌍 Overview

SmartRoute is an AI-powered logistics system that optimizes delivery routes, predicts delivery time, and improves fleet efficiency using ML + Graph Algorithms + OpenStreetMap.

---

## ⚡ Key Features

- 🚀 Route Optimization using Graph + TSP  
- ⏱️ ML-based Delivery Time Prediction  
- 🚛 Smart Vehicle Allocation  
- 📊 Real-time Dashboard Analytics  
- 🗺️ OpenStreetMap Integration  

---

## 🧠 Tech Stack

- FastAPI, Python  
- React.js  
- OSMnx, NetworkX  
- Scikit-learn, Pandas, NumPy  
- Docker, PostgreSQL  

---

## ⚙️ Setup

```bash
git clone https://github.com/Vijay2101/SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction.git
cd SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction
docker-compose up --build
Frontend: http://localhost:3000
Backend: http://localhost:8000
📸 Screenshots
🧭 Route Optimization View
<p align="center"> <img src="https://github.com/Vijay2101/SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction/blob/main/images/Screenshot%20from%202025-01-28%2011-25-18.png?raw=true" width="650"/> </p>
📍 Delivery Node Mapping
<p align="center"> <img src="https://github.com/Vijay2101/SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction/blob/main/images/Screenshot%20from%202025-01-28%2011-25-44.png?raw=true" width="650"/> </p>
🚛 Vehicle Assignment System
<p align="center"> <img src="https://github.com/Vijay2101/SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction/blob/main/images/Screenshot%20from%202025-01-28%2011-26-06.png?raw=true" width="650"/> </p>
📊 Analytics Dashboard
<p align="center"> <img src="https://github.com/Vijay2101/SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction/blob/main/images/Screenshot%20from%202025-01-28%2011-26-35.png?raw=true" width="650"/> </p>
⏱️ Delivery Time Prediction
<p align="center"> <img src="https://github.com/Vijay2101/SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction/blob/main/images/Screenshot%20from%202025-01-28%2011-26-43.png?raw=true" width="650"/> </p>
📈 Impact
⬇️ Faster deliveries
⬇️ Lower fuel cost
⬆️ Better route efficiency
⬆️ Smart fleet utilization
👨‍💻 Developer

Suraj Rawat
Full Stack + AI Developer

### 🚀 Route Optimization
- Uses **NetworkX + OSMnx graph algorithms**
- Solves **Traveling Salesman Problem (TSP)**
- Finds shortest and most efficient delivery paths

### ⏱️ Delivery Time Prediction
- ML model predicts ETA using:
  - Distance
  - Traffic
  - Weather conditions
  - Load weight

### 🚛 Smart Vehicle Assignment
- Dynamic order-to-vehicle allocation
- Capacity-based grouping
- Priority-aware scheduling

### 📊 Real-time Dashboard
- Live route visualization
- Delivery tracking
- Performance analytics

### 🐳 Scalable Architecture
- Dockerized full-stack system
- FastAPI backend + React frontend
- PostgreSQL database support

---

## 🧠 Tech Stack

### Backend
- FastAPI
- Python
- OSMnx (OpenStreetMap)
- NetworkX

### Frontend
- React.js
- JavaScript
- Google Maps API

### Machine Learning
- Scikit-learn
- Random Forest
- Pandas, NumPy

### Deployment
- Docker
- Docker Compose
- PostgreSQL

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Vijay2101/SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction.git
cd SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction
2️⃣ Run with Docker
docker-compose up --build
3️⃣ Access Application
🌐 Frontend: http://localhost:3000
🔌 Backend API: http://localhost:8000

## 📸 Screenshots

### 🧭 Route Optimization View
![Route Optimization](./images/Screenshot%20from%202025-01-28%2011-25-18.png).
👉 Displays optimized delivery route using Graph Algorithms (Shortest Path + TSP)
✔ Minimizes distance
✔ Reduces delivery time


### 📍 Delivery Node Mapping
![Node Mapping](./images/Screenshot%20from%202025-01-28%2011-25-44.png)
👉 Shows delivery locations mapped using OpenStreetMap
✔ Visualizes city-wide delivery nodes
✔ Helps spatial analysis


### 🚛 Vehicle Assignment System
![Vehicle Assignment](./images/Screenshot%20from%202025-01-28%2011-26-06.png)
👉 Demonstrates smart allocation of orders to vehicles
✔ Capacity-based grouping
✔ Priority handling


### 📊 Analytics Dashboard
![Analytics Dashboard](./images/Screenshot%20from%202025-01-28%2011-26-35.png)
👉 Real-time performance insights
✔ Delivery completion tracking
✔ Fleet efficiency monitoring


### ⏱️ Delivery Time Prediction
![Time Prediction](./images/Screenshot%20from%202025-01-28%2011-26-43.png)
👉 Machine learning-based ETA prediction
✔ Considers traffic + distance + load
✔ Accurate delivery estimation
