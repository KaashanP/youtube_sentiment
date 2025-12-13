# Reddit Sentiment Analysis - MLOps Project

![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![MLflow](https://img.shields.io/badge/MLflow-2.x-blue)
![DVC](https://img.shields.io/badge/DVC-3.x-blue)
![Docker](https://img.shields.io/badge/Docker-ready-blue)

An end-to-end MLOps project for sentiment analysis of Reddit comments, featuring experiment tracking, model versioning, and deployment.

## 🎯 Project Overview

This project demonstrates a complete MLOps pipeline for sentiment analysis:
- Data collection from Reddit
- Exploratory Data Analysis (EDA)
- Feature engineering and preprocessing
- Model training with experiment tracking (MLflow)
- Model versioning (DVC)
- API deployment (Flask)
- Containerization (Docker)

## 🛠️ Tech Stack

- **ML/DL**: scikit-learn, LightGBM, NLTK
- **Experiment Tracking**: MLflow, DagHub
- **Versioning**: DVC, Git
- **Deployment**: Flask, Docker
- **Cloud**: AWS S3 (optional)

## 📁 Project Structure

```
reddit_sentiment/
│
├── data/
│   ├── raw/               # Original Reddit data
│   └── processed/         # Cleaned and preprocessed data
│
├── notebooks/
│   ├── 01_eda.ipynb       # Exploratory Data Analysis
│   ├── 02_preprocessing.ipynb
│   └── 03_modeling.ipynb
│
├── src/
│   ├── data/              # Data collection & preprocessing
│   ├── features/          # Feature engineering
│   ├── models/            # Model training & evaluation
│   └── utils/             # Helper functions
│
├── app/                   # Flask API
├── models/                # Saved models
├── tests/                 # Unit tests
├── docker/                # Docker configuration
└── configs/               # Configuration files
```

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- Git
- Docker (optional)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/reddit_sentiment.git
cd reddit_sentiment
```

2. Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

### Usage

Coming soon...

## 📊 Model Performance

Coming soon...

## 🐳 Docker Deployment

Coming soon...

## 📝 License

MIT License

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

Built as part of MLOps learning journey.
