# CruxAI  
### Helping people find the truth in a noisy world

CruxAI is an AI-powered misinformation detection and credibility analysis platform designed to help users verify facts, analyze media credibility, monitor suspicious content, and stay informed during crisis situations.

---

# Features

## Fact Verification
Analyze claims and detect misinformation using AI-powered credibility checks.

## Agent Monitor
Track suspicious activity, monitor information patterns, and identify manipulated narratives.

## Credibility Analysis
Evaluate the trustworthiness of articles, sources, and media content.

## Crisis Alerts
Get real-time alerts and updates during critical events and emergencies.

## Media Forensics
Analyze images and media for possible manipulation or fake content detection.

## Modern UI
Clean, responsive, and user-friendly interface with dark mode support.

---

# Tech Stack

## Frontend
- React.js
- Tailwind CSS
- Vite
- Framer Motion

## Backend
- Node.js
- Express.js

## AI / APIs
- OpenAI API
- Fact-check APIs
- Media Verification APIs

## Deployment
- Vercel / Netlify (Frontend)
- Render / Railway (Backend)

---

# 📂 Project Structure

```bash
CruxAI/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── package.json
│
└── README.md
```

---

# Installation & Setup

## Clone the Repository

```bash
git clone https://github.com/your-username/cruxai.git
cd cruxai
```

---

## Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

## Setup Backend

```bash
cd backend
npm install
npm start
```

Backend runs on:

```bash
http://localhost:8081
```

---

# Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=8081
OPENAI_API_KEY=your_api_key
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```

---

# Screenshots

## Homepage
- Modern landing page
- AI-powered credibility tools
- Responsive UI
- Clean and professional design

---

# Deployment Guide

## Frontend Deployment (Vercel)

```bash
npm run build
```

Deploy the generated `dist` folder to Vercel.

---

## Backend Deployment (Render)

1. Push backend code to GitHub
2. Create a new Web Service on Render
3. Add environment variables
4. Deploy 

---

# Future Improvements

- Real-time misinformation tracking
- Browser extension support
- AI-generated credibility score
- Social media monitoring
- Multi-language support

---

# Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---



