# ViroNia: HCV Protein Classification Model
Welcome to the HCV Protein Classification Model! This project aims to classify different types of HCV (Hepatitis C Virus) proteins using a machine learning model. Here’s a straightforward guide to understanding and using this project.

**What is this Project?**

This project uses a type of deep learning model called an LSTM (Long Short-Term Memory) model to classify 9 different types of HCV proteins. The model is trained to recognize and differentiate between these proteins based on their sequences.
HCV proteins are parts of the Hepatitis C Virus. The 9 types of proteins we are classifying are:
CORE, E1, E2, NS2, NS3, NS4A, NS4B, NS5A, NS5B

**How Does it Work?**

**Data Preparation:**
We start with a dataset of protein sequences.

**Model Training:** 
The LSTM model learns to classify these sequences into one of the 9 protein types.

**Prediction:** 
You can input new protein sequences, and the model will predict which protein type they belong to.
To use this model, follow these steps:

**Install Dependencies:** Make sure you have Python and the necessary libraries installed. You’ll need: numpy, pandas, tensorflow, scikit-learn

Run the Jupyter Notebook: Open the Jupyter Notebook file (protein_prediction.ipynb) to see the code and run the model.

Input Your Data: Provide your protein sequences as input to the model.

Get Results: The model will output the predicted protein type for each sequence.
Cmpare the Model with SimpleRNN, BiLSTM, GRU (code available in repo)

Files in This Repository
protein_prediction.ipynb: The Jupyter Notebook containing the LSTM model and code for classification.
README.md: This file, providing information about the project.

**How to Contribute**
If you want to contribute to this project, feel free to:

Fork the repository.
Make your changes.
Submit a pull request with a description of what you have done.
**Contact**
For any questions or feedback, please contact me at haniaahmed1499@gmail.com

**License**
This project is licensed under the MIT License - see the LICENSE file for details.
