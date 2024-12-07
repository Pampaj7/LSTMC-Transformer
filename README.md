# Emotion Classification with LSTM and Transformer

This project aims to classify emotions in text using a combination of **LSTM** (Long Short-Term Memory) and **Transformer** layers. The model is trained on the **GoEmotions** dataset, which contains Reddit comments labeled with 27 different emotions. The goal is to predict multiple emotions for a given text, as each comment can express more than one emotion.

## Overview

The model uses a hybrid architecture combining two powerful deep learning techniques:

1. **LSTM (Long Short-Term Memory)**: Used in the encoder part of the model to capture sequential patterns and dependencies in the input text.
2. **Transformer**: Used in the decoder part, leveraging the attention mechanism to capture long-range dependencies and improve the model’s performance on multi-label classification.

The GoEmotions dataset provides labeled comments from Reddit, with 27 different emotions to predict, including emotions like **anger**, **joy**, **fear**, **love**, and **surprise**.

## Workflow

1. **Data Preprocessing**:  
   The dataset is first cleaned by selecting the relevant columns (text and emotion labels) and removing any missing or incomplete data.

2. **Model Training**:  
   The data is tokenized, padded, and fed into the LSTM-Transformer model. The model is then trained to predict the presence of emotions for each text.

3. **Prediction and Visualization**:  
   After training, the model can predict the top emotions for new texts. The results are visualized with bar charts showing the predicted probabilities for each emotion.

## Features

- Multi-label classification: The model predicts multiple emotions for each text input.
- Uses a combination of LSTM and Transformer layers to capture both sequential and long-range dependencies.
- Visualizations of training performance (loss and accuracy) and emotion predictions.

## Usage

After training the model, it can be used to predict emotions for new input text. For example, you can use the trained model to classify the emotions in a Reddit comment or any other text you want to analyze.

## Conclusion

This project demonstrates the power of combining LSTM and Transformer architectures for emotion classification tasks. By using these techniques, the model is capable of making multi-label predictions on text data.


