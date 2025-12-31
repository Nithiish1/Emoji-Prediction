# Emojify: Text to Emoji Prediction using LSTM

## Project Overview
This project implements a **deep learning–based Emojify system** that predicts the most appropriate emoji for a given text input. The model uses a **Long Short-Term Memory (LSTM)** network to capture sequential and contextual information from text and map it to corresponding emoji labels.

The objective is to demonstrate how **recurrent neural networks** can be applied to **natural language understanding tasks** such as sentiment and emotion representation.

---

## Objectives
- Convert text sequences into numerical representations  
- Learn contextual patterns using an LSTM-based neural network  
- Predict the most relevant emoji corresponding to a given sentence  
- Evaluate model performance on unseen text data  

---

## Methodology

### Data Preprocessing
- Text cleaning and tokenization  
- Conversion of words into integer sequences  
- Sequence padding to ensure fixed-length inputs  
- Encoding emoji labels into numerical format  

### Model Architecture
- Embedding Layer for word representations  
- LSTM layer to capture sequential dependencies  
- Fully Connected (Dense) output layer  
- Softmax activation for multi-class emoji prediction  

---

## Model Training
- Loss Function: Categorical Cross-Entropy  
- Optimizer: Adam  
- Batch-based training with validation monitoring  
- Performance tracking across epochs  

---

## Model Evaluation
- Accuracy evaluation on test data  
- Prediction analysis on sample text inputs  
- Comparison of predicted vs actual emoji labels  

---

## Results and Insights
- LSTM effectively captures contextual meaning in short text sequences  
- Word order and semantics significantly influence emoji prediction  
- Model generalizes well to unseen sentences with similar sentiment patterns  

---

---

## Applications
- Emoji recommendation systems  
- Sentiment-aware chat applications  
- Social media text analysis  
- NLP-based emotion recognition  

---

## Technologies Used

### Programming Language
- Python

### Libraries and Frameworks
- NumPy  
- Pandas  
- TensorFlow / Keras  
- Scikit-learn  

### Deep Learning Techniques
- Word embeddings  
- Recurrent Neural Networks (RNN)  
- Long Short-Term Memory (LSTM)  
- Sequence padding and tokenization  

---

## Author
**Makkena Nithiish**  
Dual Degree (B.Tech + M.Tech), IIT Kharagpur  
Metallurgical and Materials Engineering | Financial Engineering  

---

## Notes
This project demonstrates the application of **deep learning for sequence modeling** and serves as a foundational example of using **LSTMs for NLP classification tasks**.

