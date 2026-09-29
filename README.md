# Emotionally Adaptive Learning System

An AI-driven platform that adapts its learning content dynamically based on real-time facial expressions and voice sentiment analysis.
---

## 🌟 Key Features
* **Facial Emotion Recognition**: Analyzes facial expressions to gauge engagement and confusion.
* **Voice Sentiment Mapping**: Evaluates vocal cues and tone for supplementary validation.
* **Adaptive Content Delivery**: Dynamically adjusts learning materials based on detected emotional state.

---

## Project Structure
- `api.py` : The main backend server (FastAPI).
- `emotionally-adaptive-learning-main/` : The React/Vite frontend application.
- `models/` : (Ignored in Git) Pre-trained models for facial and voice emotion detection.
- `datasets/` : (Ignored in Git) Datasets used for training and validation.

## 🛠️ Tech Stack

### Frontend
<p align="left">
  <img src="https://img.shields.io/badge/react-%2320232d.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/typescript-%23007acc.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
</p>

### Backend & AI
<p align="left">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/fastapi-109989?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
</p>

### DevOps & Tools
<p align="left">
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

---

## 📂 Project Structure
* `api.py`: The main backend server (FastAPI).
* `emotionally-adaptive-learning-main/`: The React/Vite frontend application.
* `models/`: (Ignored in Git) Pre-trained models for facial and voice emotion detection.

---

## Setup Instructions

### Backend (Python)
1. **Create a virtual environment**:
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate

2. **Install dependencies**:
   pip install -r requirements.txt

3. **Configure Environment Variables**:
   Copy `.env.example` to `.env` and fill in your API keys:
   cp .env.example .env

4. **Run the Backend**:
   python api.py

### Frontend (React/Vite)
1. **Navigate to the frontend directory**:
   cd emotionally-adaptive-learning-main

2. **Install dependencies**:
   npm install

3. **Run the development server**:
   npm run dev

## Why are some files missing?
To keep the repository size manageable and for security reasons, the following are not included in this repository:
- **Datasets and Models**: These files are too large for GitHub. You must provide your own weights in the `models/` folder or download them from [Insert Link Here].
- **.env file**: Contains sensitive API keys. Use `.env.example` as a template.

  ## 🚀 Live Demo
<a href="https://emotionally-adaptive-learning2.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/Vercel-View_Live_Site-white?style=for-the-badge&logo=vercel&logoColor=black" alt="Live Demo Badge" />
</a>

## Troubleshooting
- **Missing Models**: If the backend fails to start because of missing `.h5` or `.keras` files, ensure you have placed the trained models in the `models/` directory.
- **API Errors**: Ensure your `GEMINI_API_KEY` is valid and has sufficient quota.
