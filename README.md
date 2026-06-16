# Emotion Detection from Text

## Overview

Emotion Detection from Text is a Natural Language Processing (NLP) and Deep Learning project that automatically identifies emotions expressed in textual data. The system analyzes user input and classifies it into one of six emotion categories: Happy, Sad, Angry, Fear, Surprise, and Neutral.

The project utilizes the GoEmotions dataset and a fine-tuned DistilBERT model to understand contextual meaning and emotional patterns in text. A graphical user interface (GUI) built with Tkinter enables real-time emotion prediction along with confidence scores, alternative predictions, and explanation-based outputs.

---

## Features

* Real-time emotion detection from text
* DistilBERT-based transformer model
* Support for six emotion categories
* Confidence score generation
* Alternative emotion prediction
* Explainable AI outputs with reasoning
* Slang normalization and negation handling
* User-friendly GUI using Tkinter
* Optimized for execution on standard CPU-based systems

---

## Problem Statement

Digital communication platforms generate massive amounts of text containing valuable emotional information. Manual analysis is time-consuming and inefficient. Existing systems often struggle with informal language, slang, negation, and real-time performance.

This project addresses these challenges by providing an accurate, efficient, and user-friendly emotion detection system capable of analyzing text in real time while generating interpretable results.

---

## Dataset

### GoEmotions Dataset

The project uses the GoEmotions dataset developed by Google.

Dataset Characteristics:

* 43,000+ text samples
* 28 fine-grained emotion labels
* Real-world Reddit comments
* Publicly available dataset

Source:
https://github.com/google-research/google-research/tree/master/goemotions

---

## Technologies Used

### Programming Language

* Python

### Libraries & Frameworks

* PyTorch
* Hugging Face Transformers
* DistilBERT
* Datasets
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Tkinter

---

## Data Preprocessing

The following preprocessing techniques were applied:

* Text normalization
* Lowercase conversion
* URL removal
* Special character removal
* Slang conversion
* Negation handling
* Tokenization using DistilBERT tokenizer

Example:

Input:
not happy today

Processed:
NEG_happy today

---

## Model Architecture

The project uses a transformer-based architecture:

DistilBERT → Contextual Embeddings → Emotion Classification Layer

Key advantages:

* Lightweight transformer model
* Faster inference
* Lower computational requirements
* Strong contextual understanding

---

## Emotion Categories

The original GoEmotions labels were mapped into six user-friendly categories:

* Happy
* Sad
* Angry
* Fear
* Surprise
* Neutral

---

## System Architecture

### Backend

* Dataset loading
* Data preprocessing
* Tokenization
* Model training
* Prediction generation

### Frontend

* GUI built using Tkinter
* User text input
* Emotion prediction display
* Confidence score display
* Reason generation engine

---

## Performance

Evaluation Metrics:

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 51.4%  |
| Precision | 38.15% |
| Recall    | 51.4%  |
| F1 Score  | 40.96% |

---

## Business Applications

This project can be used for:

* Customer Review Analysis
* Brand Sentiment Monitoring
* Social Media Analytics
* Customer Feedback Evaluation
* Market Research
* Chatbots and Virtual Assistants
* Mental Health Support Systems
* Educational Technology Platforms

---

## Future Enhancements

* Fine-tune larger transformer models
* Multi-label emotion classification
* Real-time deployment using APIs
* Web application integration
* Mobile application support
* Explainable AI visualizations
* Improved sarcasm detection
* Larger and more diverse datasets

---

## Installation

```bash
git clone <repository-url>
cd Emotional_detection_from_text
pip install -r requirements.txt
```

## Run the Project

### Train the Model

```bash
python model.py
```

### Launch GUI

```bash
python gui.py
```

---

## Project Structure

```text
Emotion_Detection_From_Text/
│
├── notebooks/
│   ├── model_training.ipynb
│   └── emotion_gui.ipynb
│
├── screenshots/
│
├── README.md
├── requirements.txt
├── LICENSE
└── outputs/
```

---

## Author

Lakshita

B.Tech (AI & ML)

## References

* Hugging Face Transformers Documentation
* PyTorch Documentation
* GoEmotions Dataset
* Python Documentation
