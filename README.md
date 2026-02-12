# Mapventure 🌍
### Interactive city exploration with Google Maps and AI

Mapventure is a web application that allows users to explore the world through Google Maps Street View. By leveraging AI, the platform identifies locations and provides rich historical and contextual information on demand. If a specific spot lacks data, the AI suggests the nearest historically significant landmark.

---

## 📸 App Preview

**Main Interface & Dashboard**
This is the primary view where users can interact with the map and manage their exploration.
<p align="center">
  <img src="./Visuals/Screenshot from 2026-02-12 20-50-58.png" width="100%" alt="Mapventure Main Dashboard" />
</p>

**Interactive Street View & AI Feedback**
When exploring in Street View, the AI provides real-time historical context and updates your location as you move.
<p align="center">
  <img src="./Visuals/Screenshot from 2026-02-12 21-11-23.png" width="48%" alt="Street View Mode" />
  <img src="./Visuals/Screenshot from 2026-02-12 21-11-39.png" width="48%" alt="AI Historical Context" />
</p>

---

## 🚀 Features

### **Current Capabilities**
* **Street View Exploration:** Navigate cities using the integrated Google Maps interface.
* **AI Historian:** Get instant historical facts and context about your current view via a single click.
* **Dynamic Location Tracking:** Your location updates in real-time as you move through the digital environment.
* **Image Recognition:** Upload photos to identify locations and learn their history.

### **Future Roadmap**
* 🌍 Global expansion (currently optimized for Sweden).
* 🔐 User accounts and saved exploration history.
* 🏆 Gamification with rankings and achievements for "Top Explorers."
* 📱 Dedicated mobile application.
* 💬 Real-time AI chat for deep-dive questions about locations.

---

## 🛠️ Tech Stack & Approach

The project is built with a modern full-stack architecture:
* **Frontend:** Vue.js + Vite for a fast, reactive UI.
* **Backend:** Node.js server handling API requests.
* **APIs:** Google Maps JavaScript API (Street View & Maps) and LLM integration for historical data.



---

## 💻 How to Run the Project

### 1. Install Dependencies
Open your terminal and run:
```sh
# Install frontend dependencies
cd ./frontend
npm install

# Install backend dependencies
cd ../backend
npm install