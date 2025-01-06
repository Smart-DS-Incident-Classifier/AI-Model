# Hadoop Log Analysis

This project aims to explore, preprocess, and train machine learning models for log classification using Hadoop log files. The logs are analyzed to detect different event categories and severity levels.

## Project Structure

- `data/`: Contains raw and processed datasets.
  - `raw/`: Original log files.
  - `processed/`: Cleaned and preprocessed logs.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model development.
- `models/`: Store the trained models.
- `reports/`: Markdown reports with analysis and evaluation results.
- `requirements.txt`: Python dependencies for the project.

## Steps Involved

1. **Data Exploration**: Analyze the raw logs, inspect for missing data, and visualize distributions.
2. **Preprocessing and Cleaning**: Tokenize unstructured logs, clean structured logs, and prepare them for model training.
3. **Model Training**: Fine-tune pre-trained models (e.g., distilBERT) for structured logs and test zero-shot classification for unstructured logs.
4. **Model Evaluation**: Evaluate models using accuracy, precision, recall, and F1-score.
5. **Model Export**: Save the trained models for future deployment.

## Requirements

- Python 3.x
- GPU (Optional, but recommended for model training)
