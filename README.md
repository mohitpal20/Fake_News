# Fake News Detection Analysis - LSTM Classification

# OverView
Create a computer program that learns to tell if news is fake or real. Use a set of articles already labeled as true or fake. Teach the program to understand the meaning of words in sentences and recognize patterns using techniques like recurrent neural networks. The program will then predict if a new article is likely to be fake or real.
# Attributes
id: unique id for a news article 

title: the title of a news article

author: author of the news article

text: the text of the article; could be incomplete

label: a label that marks the article as potentially unreliable
1: unreliable
0: reliable

Download link: https://www.kaggle.com/c/fake-news/data

Glove Embedding link: https://www.kaggle.com/anindya2906/glove6b?select=glove.6B.100d.txt

# Libraries
pandas

matplotlib

keras

tensorflow

scikit-learn

nltk

# LSTM
Long Short-Term Memory (LSTM) is a type of recurrent neural network (RNN) architecture designed to address the vanishing gradient problem, which hinders traditional RNNs from capturing long-range dependencies in sequences. LSTMs use memory cells and a gating mechanism to selectively remember or forget information over extended sequences.

Here's a simplified overview of how LSTMs work:

Memory Cells:
LSTMs have a memory cell that can store information for long durations.
This cell is modified by three gates: the input gate, the forget gate, and the output gate.

Gates:
Input Gate: Controls the flow of information into the memory cell. It decides which information is important to add to the cell.
Forget Gate: Controls the removal of information from the memory cell. It decides what information should be discarded from the cell.
Output Gate: Determines the information to be output from the memory cell.

Working:
At each time step, the LSTM receives input data and the previous hidden state and cell state.
The input gate decides which information is relevant to add to the cell state.
The forget gate removes unnecessary information from the cell state.
The output gate decides what information to output based on the cell state.
The updated cell state and the output are then passed to the next time step.

Uses:
Sequence Modeling: LSTMs are effective for tasks involving sequential data, such as natural language processing (NLP), speech recognition, and time-series analysis.
Natural Language Processing (NLP): LSTMs excel in tasks like language translation, sentiment analysis, and text generation due to their ability to capture contextual information.
Speech Recognition: LSTMs can be used to model sequential patterns in audio data, making them suitable for speech recognition applications.
Time-Series Prediction: LSTMs are adept at learning patterns and dependencies in time-series data, making them valuable for forecasting and prediction tasks.

# Neural Network

LSTM Network

Accuracy: 95.00 (Train more than 50 epochs)




