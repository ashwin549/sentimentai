# Social Media Sentiment Analysis using Bidirectional LSTM

## Overview
This project aims to analyze the sentiment of social media posts using a Bidirectional LSTM-based Recurrent Neural Network (RNN). Sentiment analysis helps determine whether a given piece of text conveys positive, negative, or neutral sentiment. It has applications in customer feedback analysis, brand monitoring, and understanding public opinion on various topics.

---
## Model Architecture
The model consists of the following layers:

1. **Embedding Layer**:
   - Input size: `max_words` (vocabulary size).
   - Output dimensions: `40` (embedding size).
   - Input sequence length: `max_len`.

2. **Bidirectional LSTM Layer**:
   - Number of units: `20`.
   - Dropout: `0.6`.
   - Captures context from both forward and backward directions in the sequence.

3. **Dense Layer**:
   - Number of units: `3` (for the three sentiment classes: Positive, Negative, Neutral).
   - Activation: `softmax` (outputs probabilities for each class).

---
