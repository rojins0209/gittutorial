# 📌 AI-Powered Stock & Search API with Phidata

## 🚀 Project Overview
This project is a FastAPI-based application that integrates **Phidata** to manage workflows, **yfinance** to fetch stock data, **duckduckgo-search** for web search, and **Groq AI** for AI-generated responses. The application is designed to be deployed using Phidata, with support for Docker and Kubernetes.

## 📂 Project Structure
```
📂 my_project
 ├── phidata.env        # Environment variables
 ├── config.py          # Phidata configuration
 ├── main.py            # FastAPI application
 ├── requirements.txt   # Dependencies
 ├── scripts/           # Utility scripts
 ├── notebooks/         # Jupyter Notebooks
 ├── workflows/         # Phidata workflows
 └── README.md          # Documentation
```

## ⚙️ Setup and Installation

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/yourusername/my_project.git
cd my_project
```

### 2️⃣ **Set Up a Virtual Environment**
```bash
python3 -m venv aienv
source aienv/bin/activate  # macOS/Linux
# OR
aienv\Scripts\activate     # Windows
```

### 3️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 4️⃣ **Initialize Phidata**
```bash
phidata init my_project
```

### 5️⃣ **Start the Application**
```bash
phidata up
```

## 🔥 API Endpoints

### **1️⃣ Home