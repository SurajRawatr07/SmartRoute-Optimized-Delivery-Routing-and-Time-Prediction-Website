# 🚚 SmartRoute – Optimized Delivery Routing & Time Prediction System

<p align="center">
  <img src="https://img.shields.io/badge/Backend-FastAPI-009688?style=for-the-badge">
  <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge">
  <img src="https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge">
  <img src="https://img.shields.io/badge/AI-ML%20Model-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Deployment-Docker-blue?style=for-the-badge">
</p>

---

## 📌 Overview

**SmartRoute** is an AI-powered logistics optimization system designed to improve delivery efficiency through:

- 🚛 Smart route optimization
- ⏱️ Delivery time prediction
- 📦 Dynamic vehicle allocation
- 📊 Real-time operational dashboard

It integrates **OpenStreetMap (OSM)** data, **machine learning models**, and graph algorithms to optimize fleet performance and reduce delivery time.

---

## ✨ Features

### 🚀 Route Optimization
- Uses **TSP (Traveling Salesman Problem)** algorithms
- Computes shortest and most efficient delivery paths using **NetworkX + OSMnx**

### 🤖 Delivery Time Prediction
- ML model trained on:
  - Distance
  - Traffic conditions
  - Weather data
- Uses **RandomForest Regressor**

### 🚚 Smart Vehicle Allocation
- Assigns orders based on:
  - Vehicle capacity
  - Priority level
  - Load weight

### 📊 Interactive Dashboard
- Real-time route visualization
- Delivery performance analytics
- Fleet tracking system

### 🐳 Scalable Architecture
- Fully containerized using **Docker & Docker Compose**
- Separate frontend and backend services

---

## 🏗️ System Architecture


---

## 🛠️ Tech Stack

### Backend
- FastAPI
- Python
- OSMnx
- NetworkX

### Frontend
- React.js
- JavaScript
- Google Maps API

### Machine Learning
- Scikit-learn
- RandomForest
- Pandas, NumPy

### Database
- PostgreSQL

### DevOps
- Docker
- Docker Compose

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/SmartRoute.git
cd SmartRoute

Run with Docker
docker-compose up --build
🌐 Access Application
Service	URL
Backend API	http://localhost:8000

Frontend Dashboard	http://localhost:3000


## Screenshots

<p align="center">
  <img src="./images/img1.png" width="400"/>
  <img src="./images/img2.png" width="400"/>
</p>

<p align="center">
  <img src="./images/img3.png" width="400"/>
  <img src="./images/img4.png" width="400"/>
</p>

<p align="center">
  <img src="./images/img5.png" width="400"/>
  <img src="./images/img6.png" width="400"/>
</p>

