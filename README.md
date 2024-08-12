# Emotions Classifier Project

## Overview
This project involved building an emotions classifier using two different machine learning models: **LSTM (Long Short-Term Memory)** and **BERT (Bidirectional Encoder Representations from Transformers)**. The objective was to perform sentiment analysis and classify textual data into various emotional categories such as sadness, joy, love, anger, fear, and surprise.

## Part 1: LSTM Model

- **Data Processing**: The dataset was cleaned and preprocessed by removing duplicates, punctuation, special characters, and stop words. The text data was tokenized and converted to lowercase.
- **Model Architecture**: A Bi-LSTM model was built using TensorFlow and Keras. The model included embedding layers, bidirectional LSTM layers, batch normalization, and dropout layers.
- **Training and Evaluation**: The model was trained for 5 epochs, achieving an accuracy of approximately 94%. The confusion matrix and classification report indicated that the model performed well in predicting dominant emotions like sadness, joy, anger, and fear, but struggled with less represented emotions like love and surprise.

## Part 2: BERT Model

- **Data Processing**: Similar preprocessing steps were applied, including tokenization using the BERT tokenizer and encoding the text data.
- **Model Architecture**: A pre-trained BERT model was fine-tuned for sequence classification. The model included dropout layers and was optimized using AdamW.
- **Training and Evaluation**: The model was trained for 3 epochs, achieving an accuracy of approximately 94%. The BERT model demonstrated high precision and recall for most emotional categories, outperforming the LSTM model, particularly in identifying emotions like sadness, joy, and anger.

## Key Insights

- **Performance Comparison**: Both models performed well, but the BERT model showed higher precision and recall across multiple emotional categories, making it a more robust tool for sentiment analysis and emotional recognition.
- **Challenges**: Both models faced challenges in accurately predicting emotions like love and surprise, indicating the need for further tuning and possibly additional data to improve performance in these categories.

## Conclusion
The project successfully demonstrated the application of advanced NLP techniques using LSTM and BERT models for emotion classification. The BERT model, in particular, showcased superior performance, highlighting its capability in handling complex sentiment analysis tasks. Further improvements can be made by addressing the challenges encountered with less represented emotions.

---
