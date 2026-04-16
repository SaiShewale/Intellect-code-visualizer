# 🚀 Intellect Code Visualizer

An advanced **AI-powered full-stack application** that transforms source code into **step-by-step explanations, visual slides, flowcharts, voice narration, and a final explainer video**.

This project combines **Frontend, Backend, and AI services** to deliver an end-to-end intelligent code understanding system.

---

## 🌟 Key Features

* 🧠 **AI Code Explanation** – Generates structured, step-by-step explanations
* 🎬 **Automatic Video Generation** – Converts explanation into a full video
* 🖼️ **Slide Generation** – Visual slides for each step
* 🔊 **Voice Narration** – Auto-generated audio explanation
* 📊 **Flowchart Creation** – Visual representation of code logic
* ⚡ **End-to-End Automation** – From code input → final video output

---

## 🏗️ System Architecture

```id="arch1"
Frontend (React - 3000)
        ↓
Backend (Spring Boot - 8081)
        ↓
AI Service (FastAPI - 8000)
        ↓
LLM Engine (Ollama - 11434)
```

---

## 🛠️ Tech Stack

### 🎨 Frontend

* React.js
* Axios
* HTML, CSS, JavaScript

### ⚙️ Backend

* Spring Boot (Java)
* REST APIs

### 🤖 AI & Processing

* FastAPI (Python)
* MoviePy (Video Generation)
* Text-to-Speech
* Flowchart Generation

### 🧠 LLM Engine

* Ollama
* llama3 model

---

## 📁 Project Structure

```id="struct1"
Intellect Code Visualizer/
│
├── frontend-react/
│   └── code-visualizer-frontend/
│
├── backend-springboot/
│   └── backend/
│
├── ai-service-python/
│
├── generated-audio/
├── generated-slides/
├── generated-videos/
├── generated-subtitles/
```

---

## ⚙️ Setup & Installation

### 🔹 1. Start LLM Server (Ollama)

```bash id="cmd1"
"C:\Users\dell\AppData\Local\Programs\Ollama\ollama.exe" serve
```

Install model:

```bash id="cmd2"
ollama pull llama3
```

---

### 🔹 2. Run AI Service (FastAPI)

```bash id="cmd3"
cd ai-service-python
venv\Scripts\activate
python -m uvicorn main:app --reload
```

➡ Runs on: `http://127.0.0.1:8000`

---

### 🔹 3. Run Backend (Spring Boot)

```bash id="cmd4"
cd backend-springboot/backend/backend
mvn spring-boot:run -DskipTests
```

➡ Runs on: `http://localhost:8081`

---

### 🔹 4. Run Frontend (React)

```bash id="cmd5"
cd frontend-react/code-visualizer-frontend
npm install
npm start
```

➡ Runs on: `http://localhost:3000`

---

## 🔄 Workflow

1. User enters code in frontend
2. Backend sends request to AI service
3. AI service:

   * Generates explanation
   * Creates slides & flowchart
   * Generates audio
   * Produces final video
4. Frontend displays video + explanation

---

## 📦 Output Generated

* 📜 Structured explanation
* 🖼️ Slides per step
* 🔊 Voice narration
* 📊 Flowchart
* 🎥 Final explanation video

---

## ⚠️ Important Notes

* Ensure Ollama is running before starting AI service
* Use **llama3** for best quality output
* Video generation may take **2–5 minutes**
* Required ports:

  * 3000 (Frontend)
  * 8000 (AI Service)
  * 8081 (Backend)
  * 11434 (Ollama)

---

## 🚀 Future Enhancements

* 🌐 Cloud deployment (Docker / Kubernetes)
* 🌍 Multi-language code support
* ⚡ Real-time streaming explanations
* 📱 Mobile-friendly UI
* 🎯 Performance optimization

---

## 👨‍💻 Author

**Sai Shewale**
B.Tech CSE | AI & Full Stack Developer

---

## ⭐ Support

If you found this project useful:

* ⭐ Star the repository
* 🍴 Fork and improve
* 📢 Share with others

---

## 💡 Why This Project Stands Out

This project demonstrates:

* Full-stack development (React + Spring Boot)
* AI integration using local LLMs
* Real-world problem solving
* Multimedia generation (audio + video + visuals)

👉 A strong showcase project for **AI + Software Engineering roles**
