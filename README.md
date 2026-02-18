# 📡 TERRA-X: Scenario Lab

**A High-Performance Predictive Simulation Platform for Global Climate & Socio-Economic Analysis.**

![TERRA-X Display](https://img.shields.io/badge/Interface-Glassmorphism-00f3ff?style=flat-square)
![Engine](https://img.shields.io/badge/AI-Llama--3.3--70B-blue?style=flat-square)
![Globe](https://img.shields.io/badge/Visualization-Three.js-white?style=flat-square)

---

## 🌎 Overview
TERRA-X is a state-of-the-art laboratory interface that allows users to manipulate global variables and witness AI-projected outcomes for any coordinate on Earth. It combines real-time weather grounding with the world's fastest LLMs to provide clinical, scientifically-accurate scenarios.

[**Live Simulation Lab**](https://nivedhn160.github.io/Terra-X/) | [**Documentation**](./TECHNICAL.md)

### 🚀 Key Features
- **Global 3D Interface**: A high-fidelity, interactive Earth visualization with day/night cycles.
- **AI Simulation Engine**: Real-time scenarios powered by Groq's Llama-3.3-70B model.
- **Omni-Search**: Locate and simulate outcomes for any city in the world.
- **Variable Manipulation**: Precise control over Carbon, Population, Economic, and Resource variables.
- **Weather Grounding**: Every simulation is grounded in the target's current live weather baseline.
- **Glassmorphic UI**: A premium, mission-control aesthetic designed for the executive suite.

---

## 🛠 Project Structure
- [**DESIGN.md**](./DESIGN.md) - Deep dive into aesthetics, UI philosophy, and typography.
- [**TECHNICAL.md**](./TECHNICAL.md) - Full technical breakdown of the architecture, data flow, and tech stack.

---

## 🏁 Getting Started

### 1. Prerequisites
- Node.js (v18+)
- Python (v3.10+)

### 2. Environment Setup
Create a `.env` file in the root directory:
```env
GROQ_API_KEY="your_groq_key"
OPENWEATHER_API_KEY="your_weather_key"
```

### 3. Launching the Lab
**Install Dependencies:**
```bash
npm install
pip install -r requirements.txt
```

**Run Development Mode:**
```bash
npm run dev
```

---

## 🌐 Deployment
- **Frontend**: Hosted on [GitHub Pages](https://nivedhn160.github.io/Terra-X/).
- **Backend**: Hosted on [Render](https://render.com/) or Railway.

---

*“Visualizing the future, one coordinate at a time.”* 📡🌎🧪
