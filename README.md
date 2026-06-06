# 🤖 AI Content Generator Platform

### (Chat + Image + Recipe Generator using Spring AI & Spring Boot)

A full-stack AI-powered web application that enables users to generate **text responses, stock images, and recipes** using natural language prompts. Built with Spring Boot, Spring AI, and a modern frontend.

---

## 🚀 Overview

This project showcases how to integrate AI into a scalable backend system using Spring AI. It combines multiple AI-powered features into a single platform:

* 💬 Conversational AI (Chat)
* 🖼️ AI Image Generation (Stock Photos)
* 🍲 Recipe Generator using AI

---

## ✨ Features

* 🔍 Generate images from natural language prompts
* 💬 Chat with AI using LLM integration
* 🍲 Generate recipes dynamically
* ⚡ REST API-based backend architecture
* 🎨 Responsive frontend with dynamic rendering
* 🔧 Configurable AI parameters (temperature, tokens, etc.)
* 🌐 Full-stack integration (React + Spring Boot)
* 🛠️ CORS handling for seamless communication

---

## 🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Spring AI
* REST APIs

### Frontend

* React.js
* HTML, CSS
* Axios / Fetch API

### AI Integration

* OpenAI / Gemini APIs (via Spring AI)

---

## 🧠 Architecture

```
Client (React)
   ↓
REST Controller (Spring Boot)
   ↓
Service Layer
   ↓
Spring AI Client
   ↓
LLM / Image Model API
```

---

## 📂 Project Structure

```
ai-content-generator/
│
├── backend/
│   ├── controller/
│   ├── service/
│   ├── config/
│   └── resources/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   └── services/
│
└── README.md
```

---

## ⚙️ Setup & Installation

### Prerequisites

* Java 17+
* Maven 
* Node.js

---

### 🔧 Backend Setup

```
git clone https://github.com/vaibhv19/AI-Content-Generator-Platform.git
cd backend

# Add your API key in application.properties
mvn spring-boot:run
```

---

### 💻 Frontend Setup

```
cd frontend
npm install
npm start
```

---

## 🔑 Configuration

Add your API key:

```
spring.ai.api.key=YOUR_API_KEY
```

---

## 📡 API Endpoints

### Chat API

```
POST /api/chat
```

### Image Generation API

```
POST /api/image
```

### Recipe Generator API

```
POST /api/recipe
```

---

## 📥 Sample Request

```json
{
  "prompt": "A futuristic city at sunset"
}
```

---

## 🎯 Use Cases

* Content creators
* Developers exploring AI integration
* Designers generating quick assets
* Students learning full-stack AI apps

---

## 🚀 Future Improvements

* 📜 Prompt history tracking
* 📥 Image download feature
* 🔐 User authentication
* 🎨 Style presets (realistic, anime, etc.)
* ☁️ Deployment on cloud (AWS / Docker)

---

## 📌 Learning Outcomes

* Integration of AI with Spring Boot using Spring AI
* Designing scalable REST APIs
* Full-stack development with React
* Handling real-world issues like CORS and API configuration

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Vaibhav Gupta**

---
