# 🌸 Iris Flower Classification – Advanced MLOps Minor Project

![MLOps](https://img.shields.io/badge/MLOps-Kubernetes-blue)
![Python](https://img.shields.io/badge/Python-3.10%2B-brightgreen)
![License](https://img.shields.io/badge/License-GPL--3.0-orange)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)

A complete end-to-end MLOps minor project for classifying Iris flowers using machine learning. This repository demonstrates robust data pipelines, automated training, containerization, Kubernetes deployment, and a web application for interactive inference. The solution is designed for reproducibility, scalability, and serves as a practical foundation for learning MLOps.

> 📁 **Repository:** `Advanced_MLOPS_Project8_Minor_Project1`

---
<p align="center">
  <img src="https://housing.com/news/wp-content/uploads/2022/11/iris-flower-compressed.jpg" width="800" height="533">
</p>



## 🚀 Project Highlights

- 🌷 **Iris Classification:** Predicts Iris species from flower measurements
- 🏗️ **Modular MLOps Workflow:** Clear separation of code, data, pipeline, and deployment
- 🐳 **Dockerized:** Easily build and deploy as a container
- ☸️ **Kubernetes-Ready:** Out-of-the-box deployment with a provided manifest
- 🌐 **Web App:** User-friendly interface for live classification

---

## 🧠 Technical Stack

### 🛠️ Core Technologies
![Python](https://img.shields.io/badge/Python-3.10%2B-brightgreen)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Deploy-blue)
![Flask](https://img.shields.io/badge/Flask-WebApp-lightgrey)

### 📦 Libraries & Utilities
- Pandas, NumPy, Scikit-learn (ML/data)
- Flask (web app)
- YAML (config management)
- HTML/CSS (UI)
- Jupyter Notebook (EDA, prototyping)

---

## 🏗️ Project Structure

```bash
Advanced_MLOPS_Project8_Minor_Project1/
├── DATA/
│   └── data.csv                     # Iris dataset
├── CODE/
│   ├── notebook/
│   │   └── iris.ipynb               # EDA & prototyping
│   ├── pipeline/
│   │   ├── __init__.py
│   │   └── training_pipeline.py     # ML pipeline orchestration
│   ├── src/
│   │   ├── __init__.py
│   │   ├── custom_exception.py
│   │   ├── data_processing.py
│   │   ├── logger.py
│   │   └── model_training.py
│   ├── static/
│   │   └── style.css                # Web app styling
│   ├── templates/
│   │   └── index.html               # Web app template
│   ├── Dockerfile                   # Docker build file
│   ├── application.py               # Flask app entry point
│   ├── kubernetes-deployment.yaml   # Kubernetes deployment manifest
│   ├── requirements.txt             # Python dependencies
│   ├── setup.py                     # Package info
│   ├── LICENSE
│   ├── PDF AND NOTES.pdf            # Documentation/workflow
│   └── README.md
├── SETUP INSTRUCTION                # Deployment & usage guidance
├── .gitignore
```

---

## ⚡ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/mdzaheerjk/Advanced_MLOPS_Project8_Minor_Project1.git
cd Advanced_MLOPS_Project8_Minor_Project1/CODE
```

### 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the ML pipeline
```bash
python pipeline/training_pipeline.py
```

### 5. Launch the web application
```bash
python application.py
```
Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 🐳 Docker & Kubernetes Deployment

- **Docker:**  
  Build and run the project in a container using the provided `Dockerfile`.

- **Kubernetes:**  
  Deploy on a Kubernetes cluster using `kubernetes-deployment.yaml`.

- **Setup Guidance:**  
  See `SETUP INSTRUCTION` and `PDF AND NOTES.pdf` for deployment and configuration help.

---

## 📊 Example Use Cases

- **Iris Flower Classification:** Predicts the species of an Iris flower given feature inputs
- **Web App Demo:** Enter flower measurements for instant species prediction
- **MLOps Learning:** Demonstrates automation, CI/CD, and scalable cloud deployment

---

## ✍️ Author

**Mohammed Zaheeruddin**  
🎓 First-Year B.Tech Student | AI/ML & GenAI Enthusiast  
🏫 Shetty Institute of Technology, Gulbarga  
📧 info.zaheerjk@gmail.com

---

## 📜 License

This project is licensed under the **GPL-3.0 License** – see the LICENSE file for details.

---

#### Key Features:
1. End-to-end Iris classification pipeline with modular codebase
2. Scalable, production-ready Docker and Kubernetes deployment
3. User-friendly web interface for real-time inference
4. Designed for learning, demonstration, and real-world adaptation
