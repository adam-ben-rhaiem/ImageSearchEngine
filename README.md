# 🔍 ImageSearchEngine
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


## 🏗️ Architecture Overview 

This project is a powerful image search engine that combines the strengths of FastAPI for backend processing and Streamlit for an intuitive frontend experience. The system allows users to upload images and find visually similar images from an indexed collection.

### ⚙️ Backend (FastAPI)
The backend is built with FastAPI and provides robust API endpoints for:

#### 📥Image Indexing 

- Stores images and their visual features in Elasticsearch

- Processes images to extract distinctive visual characteristics

#### 🔎Image Search

- Accepts query images and returns visually similar results

- Leverages Elasticsearch for fast similarity searches

- Utilizes advanced computer vision techniques for feature extraction

### 💻Frontend (Streamlit) 
The user-friendly interface includes:

#### 📤Image Upload 

- Simple drag-and-drop or file selection

- Preview of uploaded images

#### 🖼️ Search Results 

- Grid display of similar images

- Visual similarity scores

- Interactive browsing experience

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- Elasticsearch 7.x running locally or remotely
- (Optional) GPU for faster feature extraction

```bash
# Clone the repository
git clone https://github.com/adam-ben-rhaiem/ImageSearchEngine.git
cd ImageSearchEngine

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt


