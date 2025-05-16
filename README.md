# 🔍 ImageSearchEngine - CBIR System

![CBIR Demo](https://via.placeholder.com/800x400?text=Image+Search+Demo) [^1]
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.68+-green)](https://fastapi.tiangolo.com)
[![Elasticsearch](https://img.shields.io/badge/Elasticsearch-7.x-yellow)](https://elastic.co)
[![License](https://img.shields.io/badge/License-MIT-red)](LICENSE)

A powerful Content-Based Image Retrieval (CBIR) system that finds visually similar images using deep learning and Elasticsearch.

## 🚀 Features

- ⚡ **Blazing fast** image similarity search
- 🖼️ Supports **multiple feature extraction** methods (CNN, Color Histograms, etc.)
- 📊 **Scalable architecture** with Elasticsearch backend
- 🌈 **Interactive Streamlit UI** for easy exploration
- 🔌 **REST API** for integration with other applications

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- Elasticsearch 7.x running locally or remotely
- (Optional) GPU for faster feature extraction

```bash
# Clone the repository
git clone https://github.com/skanderyaakoubi/cbir_project.git
cd cbir_project

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt
