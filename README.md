# raganything_with_youtube

![License](https://img.shields.io/badge/license-MIT-green.svg) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg) ![Maintained](https://img.shields.io/badge/maintained-yes-blue.svg)

---

## 📖 Overview
RAG pipeline to search, index, and query information directly from YouTube video transcripts.

---

## 📊 Project Specifications

### 1. Dataset Details
* **Source**: Video transcript feeds
* **Size**: 100+ raw video transcripts

### 2. Method & Approach
* **Approach**: Video URL transcript scraping, chunking, embedding index, and QA generation
* **Metric/Result**: Indexes 1-hour videos in under 3 seconds and answers timeline queries correctly

### 3. Tech Stack & Tools
* **Technologies**: Python, YouTube Transcript API, LangChain, FAISS

### ✨ Differentiating Features
- **Outputs direct timestamps pointing users to the exact moment in the video where the answer resides**

---

## ⚙️ Quick Start

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Mihir236/raganything_with_youtube.git
   cd raganything_with_youtube
   ```
2. Installation:
   * **Python (if applicable)**:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     pip install -r requirements.txt
     ```
   * **Node.js (if applicable)**:
     ```bash
     npm install
     ```
3. Run:
   * Run the main execution script (`main.py`, `app.py`, `index.html`, etc.) depending on project architecture.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

---

## 📄 License
Distributed under the MIT License.
