# Project Information: Disease Prediction Classifier

## Project Title
**COVID-19 Detection from Unstructured Medical Text**

## Course
IST 664: Natural Language Processing

## Team Members
Dawryn Rosario, Semi Babafemi

## Summary of Work
This project presents a robust end-to-end pipeline that leverages natural language processing (NLP) and machine learning to detect potential COVID-19 cases from clinical notes. Using the MIMIC-IV dataset, CDC COVID-19 surveillance data, and additional unstructured medical text, the pipeline applies Named Entity Recognition (NER) to extract symptoms, severity, and time indicators. These extracted features are then combined with structured patient data to train transformer-based classification models.

The system demonstrates a complete text mining lifecycle: from raw medical notes to risk probability scores using rule-based and deep learning–based NER. Project components include text preprocessing, data integration, entity extraction, feature engineering, classification modeling, and detailed evaluations.

## What I'm Most Proud Of
I'm proud of the depth and integration this project achieved—blending structured and unstructured data, combining rule-based logic with transformer models, and creating a replicable pipeline for clinical insight generation. Our collaboration enabled modular design across Jupyter notebooks, Python modules, and supporting scripts, culminating in a scalable solution for real-world medical text classification.

## Project Contents

- `assets/videos/`: Contains a demonstration video showing the pipeline in action

- `data/`: Organized dataset directory with structured and unstructured data
  - `raw/`, `processed/`, `interim/`, `external/mimic/`: Support data flow and preprocessing

- `docs/`: Project documentation and explanations
  - `project_overview.md`, `data_strategy.md`, `README_analysis.md`

- `notebooks/`: Step-by-step Jupyter notebooks detailing feature extraction, NER, classification modeling, and data exploration
  - Includes: `03_model_building.ipynb`, `04_ner_extraction_pipeline.ipynb`, etc.

- `output/`: Stores classification results and visualizations

- `results/analysis/plots/`: Contains graphs and visual analysis of model outputs

- `src/`: Python source code for NER, data integration, modeling, and utility scripts

- `tests/`: Python test files for unit testing entity extraction and dataset preparation

- `models/`: Folder for saved ML models

- `presentations/`: Slide deck and write-up in `.pdf`, `.pptx`, and `.docx` formats

- `run_pipeline.py`: Master script to execute the full NER-to-classification pipeline

- `requirements.txt`: Python dependencies for project reproducibility

## Required Software
- Python 3.8+
- Jupyter Notebook
- Pandas, NumPy, spaCy, Transformers, Torch
- Git (for version control)
- Basic terminal/command-line usage

---

_Last updated: July 2025_