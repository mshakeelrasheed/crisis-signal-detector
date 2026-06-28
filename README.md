# 🧠 Crisis Signal Detector

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=for-the-badge)
![BERT](https://img.shields.io/badge/BERT-NLP-success?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-ff4b4b?style=for-the-badge&logo=streamlit)
![Docker](https://img.shields.io/badge/Docker-Container-blue?style=for-the-badge&logo=docker)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

## 📖 Project Overview

**Crisis Signal Detector** is an AI-powered Natural Language Processing (NLP) application that identifies crisis-related text using a fine-tuned **BERT (Bidirectional Encoder Representations from Transformers)** model.

The system analyzes user input in real time and classifies it as either **Crisis Signal** or **Normal Text**, displaying the prediction along with a confidence score through an interactive web dashboard.

This project was developed as the **final capstone project** during the **NAVTTC-sponsored Artificial Intelligence & Machine Learning training program** conducted at **Corvit Systems Bahawalpur**.

---

# 🚀 Live Demo

🔗 **Hugging Face Space**

**https://huggingface.co/spaces/mshakeelrasheed/crisis-signal-detector**

---

# ✨ Features

- ✅ Real-time text classification
- ✅ Fine-tuned BERT model
- ✅ Interactive Streamlit dashboard
- ✅ Confidence score visualization
- ✅ Probability graph
- ✅ Hugging Face deployment
- ✅ Docker support
- ✅ User-friendly interface

---

# 🧠 Model Architecture

The application follows the workflow below:

```
User Input
      │
      ▼
 Text Preprocessing
      │
      ▼
 BERT Tokenizer
      │
      ▼
 Fine-tuned BERT Model
      │
      ▼
 Softmax Probability
      │
      ▼
 Crisis / Normal Prediction
```

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Deep Learning | PyTorch |
| NLP | Hugging Face Transformers |
| Model | BERT |
| Interface | Streamlit |
| Deployment | Hugging Face Spaces |
| Containerization | Docker |
| Data Processing | Pandas, NumPy |

---

# 📂 Repository Structure

```
crisis-signal-detector/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── README.md
├── LICENSE
│
├── model/
│   ├── config.json
│   ├── tokenizer.json
│   ├── tokenizer_config.json
│
├── screenshots/
│   ├── dashboard.png
│   ├── architecture.png
│
├── notebook/
│   └── training.ipynb
│
└── presentation/
    └── CrisisSignalDetector.pdf
```

---

# 📸 Screenshots

## Dashboard

![Dashboard](screenshots/dashboard.png)

---

## System Architecture

![Architecture](screenshots/architecture.png)

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/crisis-signal-detector.git
```

Move into the project folder

```bash
cd crisis-signal-detector
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

# 📊 Results

The deployed application performs real-time inference using a fine-tuned BERT model and displays:

- Prediction (Crisis / Normal)
- Confidence Score
- Probability Visualization

---

# 📁 Project Documentation

The complete project presentation is available in the **presentation/** directory.

It contains:

- Problem Statement
- Dataset Overview
- Model Architecture
- Deployment Process
- Results
- Future Improvements

---

# ⚠ Model Weights

The trained model weights (`model.safetensors`) are **not included** in this repository due to GitHub file size limitations.

The complete deployed application can be accessed through the Hugging Face Live Demo.

---

# 🔮 Future Improvements

- Multi-language support
- Mobile application integration
- Explainable AI (XAI)
- REST API development
- Continuous model retraining
- Improved dataset diversity

---

# 👨‍💻 Author

**Muhammad Shakeel Rasheed**

BS Artificial Intelligence Student

Islamia University Bahawalpur

---

# 📄 License

This project is licensed under the MIT License.
