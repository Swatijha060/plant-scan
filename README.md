# 🌿 Plant Analysis Tool

## 🧠 Overview
The **Plant Analysis Tool** is a Node.js + Express web API that uses **Google’s Gemini Generative AI** to analyze plant images.  
It identifies plant species, evaluates health, and provides care recommendations based on an uploaded image.  
Perfect for gardeners, researchers, or anyone curious about their plants!

---

## 🚀 Features
✅ Upload an image of a plant using Postman or a web frontend  
✅ AI-powered analysis of plant species, health, and care instructions  
✅ Generates detailed text output  
✅ Optional PDF download of the analysis report  
✅ Automatically deletes uploaded images after analysis  
✅ Easy integration with any frontend  

---

## 🏗️ Tech Stack
- **Node.js** (with Express)
- **Multer** for image uploads
- **Google Generative AI SDK (@google/genai)**
- **PDFKit** for generating PDF reports
- **dotenv** for environment variable management

---

## ⚙️ Installation and Setup
### 1️⃣ Install dependencies
```bash
npm install
```
### 2️⃣ Set up environment variables

Create a .env file in the root directory:
```bash
GEMINI_API_KEY=your_google_gemini_api_key_here
PORT=your_port_number
```

### 3️⃣ Run the server
```bash
node app.js or  node server.js
```
OR
if you are using nodemon

```bash
npm run dev
```


❤️ Credits

Developed by Swati Jha
Powered by Google Generative AI and Node.js

“Turning leaves into insights — one photo at a time 🌱”

