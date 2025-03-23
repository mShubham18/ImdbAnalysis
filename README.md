# IMDB Sentiment Analysis using Simple RNN

## 📌 Project Overview
This project implements Sentiment Analysis on IMDB movie reviews using a Simple RNN model. The model is trained to classify reviews as positive or negative based on the text input. The project is deployed as a Streamlit web application.

The dataset used for training is the IMDB Large Movie Review Dataset, which contains 50,000 reviews labeled as either positive or negative. The model processes user-provided text by converting words into numerical sequences using a predefined word index. The sequences are padded to a fixed length before being fed into the Simple RNN model for classification.

The Streamlit web application provides a user-friendly interface where users can enter a movie review and receive real-time sentiment classification. It integrates TensorFlow/Keras for deep learning inference and NumPy for data preprocessing. The model outputs a sentiment score, which determines whether the review is classified as positive or negative.


## 🚀 Live Link
[Streamlit Web Application](https://imdbdata-sentiment-analysis.streamlit.app/)

## 📂 Project Structure
```
IMDBANALYSIS/
│── imdb/                     # IMDB dataset directory (if applicable)
│── model/                    # Model and dataset directory
│   ├── RNNmodel.h5           # Trained RNN model file
│   ├── .gitignore            # Git ignore file
│   ├── Dataset.csv           # IMDB dataset file
│   ├── embedding.ipynb       # Notebook for word embeddings
│   ├── IMDBPrediction.py     # Main script for prediction
│   ├── model.h5              # Another model file
│   ├── prediction.ipynb      # Notebook for making predictions
│   ├── requirements.txt      # Python dependencies
│   ├── RNNImplementation.ipynb # Notebook for training the RNN model
```

## 🚀 How to Run the Project
### **1️⃣ Install Dependencies**
Run the following command to install the required Python libraries:
```bash
pip install -r requirements.txt
```

### **2️⃣ Run the Streamlit Web App**
Execute the following command to launch the web application:
```bash
streamlit run IMDBPrediction.py
```

## 🛠️ Model Details
- **Dataset**: IMDB Movie Reviews
- **Model Architecture**: Simple RNN
- **Training Framework**: TensorFlow/Keras
- **Max Review Length**: 500 words

## 🌟 Features
✅ Pre-trained RNN model for sentiment analysis  
✅ Takes user input as a movie review and classifies sentiment  
✅ Uses **word embeddings** for text processing  
✅ Deployed as a **Streamlit web app**  

---
Happy Coding ;)