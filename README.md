# 🦕 Deno + LlamaIndex + React Full-Stack Web App

![Deno](https://img.shields.io/badge/Deno-1.39.0-blue?logo=deno) ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-0.1.8-green) ![React](https://img.shields.io/badge/React-17.0.2-blue)

🚀 A full-stack web application built using **Deno**, **LlamaIndex**, and **React**. This project features a simple API, an AI-powered query engine, and a frontend counter app.

---

## 📌 Features
✅ **Deno Web Server** - Handles HTTP requests efficiently.  
✅ **LlamaIndex Integration** - Processes document queries from a dataset.  
✅ **React Frontend** - Displays an interactive counter.  
✅ **Modular Design** - Easily extendable for additional features.  

---

## 📂 Project Structure
```bash
📦 project-root
 ┣ 📂 data             # Data directory for LlamaIndex
 ┣ 📂 frontend         # React frontend
 ┣ 📂 backend         # Deno API & LlamaIndex setup
 ┣ 📜 utils.ts        # Helper functions
 ┣ 📜 server.ts       # Main server file
 ┣ 📜 README.md       # Project documentation
```

---

## 🛠️ Installation & Setup

### 1️⃣ **Clone the Repository**
```sh
git clone https://github.com/your-repo/deno-llamaindex-react.git
cd deno-llamaindex-react
```

### 2️⃣ **Install Dependencies**
Ensure you have **Deno** installed. Then, install dependencies:
```sh
deno task install
```

### 3️⃣ **Run the Backend**
```sh
deno run --allow-net --allow-read backend/server.ts
```

### 4️⃣ **Run the Frontend**
```sh
deno run --allow-net frontend/main.tsx
```

---

## 📌 API Endpoints

| Method | Endpoint       | Description |
|--------|--------------|-------------|
| GET    | `/`          | Returns "Command Given!" |
| POST   | `/query`     | Processes AI queries |

#### Example Query Request:
```json
{
  "query": "What is the meaning of life?"
}
```

---

## 🎨 Visual Overview
### **Architecture Diagram**
```
[ User ] → [ React Frontend ] → [ Deno API ] → [ LlamaIndex ]
```

---

## 🎭 Stickers & Badges
[![Powered by Deno](https://img.shields.io/badge/Powered%20By-Deno-black?logo=deno)](https://deno.land/) [![Built with React](https://img.shields.io/badge/Built%20With-React-blue?logo=react)](https://reactjs.org/)  

---

## 🚀 Future Enhancements
- ✅ Add authentication using JWT
- ✅ Implement a database for query storage
- ✅ Improve UI with TailwindCSS

---

## 🤝 Contributing
Feel free to submit a **pull request** or report issues in the [Issues](https://github.com/your-repo/issues) tab!

---
