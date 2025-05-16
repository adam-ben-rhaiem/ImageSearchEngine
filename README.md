# 🔍 ImageSearchEngine - CBIR System
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.68+-green)](https://fastapi.tiangolo.com)
[![Elasticsearch](https://img.shields.io/badge/Elasticsearch-7.x-yellow)](https://elastic.co)


A powerful Content-Based Image Retrieval (CBIR) system that finds visually similar images using deep learning and Elasticsearch.

## 🚀 Features

- ⚡ **Blazing fast** image similarity search
- 🖼️ Supports **multiple feature extraction** methods (CNN, Color Histograms, etc.)
- 📊 **Scalable architecture** with Elasticsearch backend
- 🌈 **Interactive Streamlit UI** for easy exploration
- 🔌 **REST API** for integration with other applications
## 🏗️ Project Structure
cbir_project/
├── backend/               # FastAPI application

│   ├── app.py            # Main API endpoints

│   ├── feature_extractor # Image feature extraction

│   └── elastic/          # Elasticsearch operations

├── frontend/             # Streamlit UI

│   └── app.py            # User interface

├── tests/                # Unit tests

├── requirements.txt      # Python dependencies

└── README.md            # You are here!

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- Elasticsearch 7.x running locally or remotely
- (Optional) GPU for faster feature extraction

```bash
# Clone the repository
git clone https://github.com/adam-ben-rhaiem/ImageSearchEngine.git
cd cbir_project

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt


