# Semantic Book Recommender with LLMs

A machine learning project that provides intelligent book recommendations using Large Language Models (LLMs). The system analyzes book content to provide personalized recommendations based on semantic search, genre classification, and sentiment analysis.

## Features

- **Text Data Cleaning**: Preprocessing and cleaning of book data
- **Semantic Vector Search**: Find similar books using natural language queries
- **Genre Classification**: Automatic fiction/non-fiction classification using zero-shot learning
- **Sentiment Analysis**: Analyze emotional tones of books (suspense, joy, sadness)
- **Web Interface**: User-friendly dashboard built with Gradio

## Project Structure

- `data-exploration.ipynb`: Data cleaning and preprocessing notebook
- `vector-search.ipynb`: Implementation of semantic search functionality
- `text-classification.ipynb`: Genre classification using zero-shot learning
- `sentiment-analysis.ipynb`: Emotion extraction and sentiment analysis
- `gradio-dashboard.py`: Web application interface

## Requirements

- Python 3.11
- Dependencies:
  - kagglehub
  - pandas
  - matplotlib
  - seaborn
  - python-dotenv
  - langchain-community
  - langchain-opencv
  - langchain-chroma
  - transformers
  - gradio
  - notebook
  - ipywidgets

## Installation

1. Clone the repository
2. Install dependencies:
```python
pip install -r requirements.txt
```

## Usage
Run the Jupyter notebooks in sequence to process data and train models
3. Run the web interface:
```python
python gradio-dashboard.py
```

In order to create your vector database, you'll need to create a .env file in your root directory containing your OpenAI API key. Instructions on how to do this are part of the tutorial.

The data for this project can be downloaded from Kaggle. Instructions on how to do this are also in the repo.

