# 🏷️ Named Entity Recognition (NER) Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://tensorflow.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

> **Advanced Named Entity Recognition using BiLSTM-LSTM Architecture with TensorFlow/Keras**

A comprehensive implementation of a state-of-the-art Named Entity Recognition model that can identify and classify named entities such as person names, organizations, locations, dates, and more from text data.

## 🚀 Features

- **🧠 Smart Model**: BiLSTM + LSTM for text  
- **📊 Explore Data**: Easy data check & prep  
- **🎯 High Accuracy**: >99% on NER tasks  
- **📓 Notebook**: Step-by-step guide  
- **💾 Save & Load**: Keep your model  
- **🔍 Predict Fast**: Find entities in text


### ⚙️ Model Parts
- **🔹 Embedding**: Turns words into 64-dim vectors  
- **↔️ BiLSTM**: Reads text forwards & backwards  
- **💡 LSTM**: Processes sequence with dropout  
- **📊 TimeDistributed Dense**: Predicts tags for each word

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/Sampavi01/NER-model.git
cd NER-model
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Prepare Your Dataset
Ensure your dataset (`NER dataset.csv`) has the following columns:
- `Sentence #`: Sentence identifier
- `Word`: Individual words/tokens
- `POS`: Part of speech tags
- `Tag`: Named entity tags (e.g., B-PER, I-ORG, O)

### 4. Run the Notebook
```bash
jupyter notebook NER_Analysis.ipynb
```

### Supported Entity Tags:
- **B-PER, I-PER**: Person names
- **B-ORG, I-ORG**: Organizations
- **B-LOC, I-LOC**: Locations
- **B-DATE, I-DATE**: Dates
- **B-MISC, I-MISC**: Miscellaneous entities
- **O**: Non-entity tokens


### 💼 Business Use
- **📞 Support**: Find companies & products  
- **📄 Legal**: Detect parties, dates, locations  
- **📰 News**: Track entities in articles  
- **💬 Social Media**: Monitor brands & sentiment  

### 🔬 Research Use
- **📚 Papers**: Extract citations & refs  
- **🏥 Medical**: Detect patient info & diagnoses  
- **💰 Finance**: Find companies, amounts, dates



```
ner-model
├── NER_Analysis.ipynb          # Main Jupyter notebook
├── NER dataset.csv             # Training dataset
├── README.md                   # This file
├── requirements.txt            # Python dependencies
       

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
