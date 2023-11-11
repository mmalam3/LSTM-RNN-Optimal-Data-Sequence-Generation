# Sequence Modeling and Optimal Data Sequence Generation using LSTM-based RNN
This repository contains the **TensorFlow** and **Python** implemention of an **LSTM-based Recurrent Neural Network (RNN)** that is trained to discover sequential data patterns given a set of input data sequences and generate optimal data sequences with a user-defined *seed* as the starting node.

# Dataset
We use a number of preprocessed datasets located at the ***data*** directory to select the input data sequences for training the neural network. These datasets were from prepared from the following dataset:

**Dataset Name**: Peeves: Physical Event Verification in Smart Homes[1]

**Link**: https://ora.ox.ac.uk/objects/uuid:75726ff7-fee1-420d-8a17-de9572324c7d

**About the dataset**: https://ora.ox.ac.uk/objects/uuid:75726ff7-fee1-420d-8a17-de9572324c7d/download_file?file_format=pdf&safe_filename=readme.pdf&type_of_work=Dataset).

# Codebase Information
**Language used**: Python

**ML Libraries used**: TensorFlow

**Libraries used for visualization**: Matplotlib

**Other Libraries used**: Numpy, pandas

# Usage
1. Install the following dependencies: `TensorFlow`, `Python`, `NumPy`, `pandas`, and `Matplotlib`.
2. [**optional**] Use the pre-trained model ***trained_model.keras*** located at the ***models*** directory.
3. Simply execute the `LSTM_RNN_Data_Gen.py` script or run the notebook `LSTM_RNN_Data_Gen.ipynb` in Google Colab.

# Performance Evaluation
The following figures shows the training and validation accuracy and loss of the LSTM-based RNN used to extract the sequential data patterns from a set of input data sequences. 

![Training and validation accuracy of the LSTM-based RNN](https://github.com/mmalam3/LSTM-RNN-Optimal-Data-Sequence-Generation/blob/main/evaluation/model_accuracy.png) 

![Training and validation loss of the LSTM-based RNN](https://github.com/mmalam3/LSTM-RNN-Optimal-Data-Sequence-Generation/blob/main/evaluation/model_loss.png) 


# Reference
[1] Birnbach, S., & Eberz, S. (2019). Peeves: Physical Event Verification in Smart Homes. University of Oxford.

