# Stock Photo Generator

A full-stack AI web app that generates text responses, stock photo images, and recipes from natural language prompts.

Built with:
* React frontend
* Spring Boot backend
* Spring AI for OpenAI-powered chat, image generation, and recipe creation

---

## Overview

This repository is organized into two main folders:
* `frontend/` — React user interface
* `backend/` — Spring Boot API server

The app uses a React dashboard to call backend endpoints for AI chat, image generation, and recipe creation.

---

## Features

* 💬 AI chat responses
* 🖼️ AI-generated images from prompt text
* 🍲 AI recipe generation from ingredients and cuisine preferences
* 🌐 React frontend + Spring Boot backend integration
* ⚙️ CORS-enabled local development

---

## Tech Stack

### Backend
* Java 21
* Spring Boot
* Spring AI
* Maven

### Frontend
* React.js
* JavaScript
* Create React App
* Fetch API

---

## Project Structure

```
frontend/
  package.json
  package-lock.json
  public/
  src/
backend/
  pom.xml
  mvnw
  mvnw.cmd
  HELP.md
  src/
README.md
```

---

## Prerequisites

* Java 21
* Maven (or use the bundled Maven wrapper)
* Node.js 18+ and npm

---

## Setup

### Backend

1. Open `backend/src/main/resources/application.properties`
2. Set your OpenAI key:

```properties
spring.ai.openai-key=${OPENAI_API_KEY}
```

3. Start the backend:

```powershell
cd backend
.\mvnw.cmd spring-boot:run
```

### Frontend

```powershell
cd frontend
npm install
npm start
```

The frontend runs on `http://localhost:3000` and calls the backend at `http://localhost:8080`.

---

## API Endpoints

### Chat

```
GET /ask-ai?prompt=<your prompt>
```

### Image Generation

```
GET /generate-image?prompt=<your prompt>
```

### Recipe Generator

```
GET /recipe-creator?ingredients=<ingredients>&cuisine=<cuisine>&dietaryRestrictions=<restrictions>
```

---

## Build

### Backend

```powershell
cd backend
.\mvnw.cmd -DskipTests compile
```

### Frontend

```powershell
cd frontend
npm run build
```

---

## Notes

* The backend is configured to allow cross-origin requests from `http://localhost:3000`.
* If you need to use a different OpenAI environment variable name, update `application.properties` accordingly.

---

## License

MIT


## 👨‍💻 Author

**Vaibhav Gupta**

---
