

# 🚀 SynnccIT | AI-Powered Cloud IDE

**SynnccIT** is a next-generation **AI-driven Cloud Integrated Development Environment (IDE)** designed to streamline coding, testing, and collaboration.
It combines a **modern frontend**, **distributed micro-backend architecture**, and an **intelligent AI agent** to deliver a seamless developer experience across platforms.

🔗 **Live Demo:** [https://synncc-it.vercel.app/](https://synncc-it.vercel.app/)
🎥 **Demo Video:** [https://youtu.be/6MdZ4L3TBNQ](https://youtu.be/6MdZ4L3TBNQ)

---

# ✨ Overview

SynnccIT empowers developers with:

* ⚡ Real-time cloud coding environment
* 🤖 AI-powered development assistance
* 💻 Cross-platform terminal execution
* 📂 Interactive file system management
* 🧪 Integrated testing & simulation services
* 🎨 Premium modern UI

The platform follows a **modular microservice architecture**, enabling scalability, flexibility, and independent service deployment.

---

# 🚀 Key Features

## 🤖 AI Agent Integration

* Code generation & optimization
* Terminal command translation
* Planning & debugging assistance
* Natural language development workflow

## 💻 Cross-Platform Terminal

* WebSocket-based real-time terminal
* Windows support (cmd / PowerShell)
* Unix/macOS support (bash / zsh)

## 📂 Interactive File Explorer

* Full project file system navigation
* File creation, editing, deletion
* Native file system access support

## 📝 Modern Code Editor

* Syntax highlighting
* Multi-file editing
* Smooth developer experience

## 🧪 Testing & Simulation Engine

* Automated test execution
* Flowchart simulation
* Code evaluation services

## 📊 Status Monitoring Service

* Backend service health monitoring
* System status tracking

## 🎨 Premium UI/UX

* Responsive modern design
* Tailwind + shadcn component system
* Dark-mode friendly architecture

---

# 🛠️ Tech Stack

## Frontend

* **Framework:** React 18 + TypeScript
* **Styling:** Tailwind CSS, shadcn/ui, Radix UI
* **Build Tool:** Vite
* **Terminal Engine:** xterm.js

## Backend

* **Framework:** Python 3.10+ with FastAPI
* **AI Engine:** Google Generative AI (Gemini Flash 1.5)
* **Async Tools:** asyncio
* **Terminal Utilities:** PTY (Unix)
* **File Watching:** watchfiles

---

# 🏗️ Architecture

The platform follows a **distributed microservice architecture**:

```
SynnccIT/
├── src/                        # Frontend React App
├── DeveloperPage_Backend/      # Core IDE Backend (File System + Terminal)
├── AgentPage_Backend/          # AI Agent Service
├── TestingPage_Backend/        # Testing & Simulation Engine
└── StatusPage_Backend/         # Monitoring & Health Service
```

---

# 🚥 Getting Started

## ✅ Prerequisites

* Node.js ≥ 18
* Python ≥ 3.10
* Gemini API Key (optional for AI features)

---

## 📥 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/SynnccIT.git
cd SynnccIT
```

### 2️⃣ Frontend Setup

```bash
npm install
```

### 3️⃣ Backend Setup (Core IDE)

```bash
cd DeveloperPage_Backend
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### Start Frontend

```bash
npm run dev
```

### Start Backend

```bash
cd DeveloperPage_Backend
uvicorn app:app --host 127.0.0.1 --port 8000 --reload
```

---

# 🔐 Environment Variables (Optional)

Create a `.env` file:

```
GEMINI_API_KEY=your_api_key
```

---

# 📈 Future Enhancements

* Real-time collaborative coding
* Containerized execution sandbox
* Plugin marketplace
* GitHub integration
* AI code review & refactoring engine
* Multi-language runtime support

---

# 🤝 Contributing

Contributions are welcome 🎉

1. Fork the repo
2. Create feature branch
3. Commit changes
4. Submit Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

