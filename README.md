# Customer Churn Prediction Using Artificial Neural Network (ANN)
## Project Overview
This project aims to predict customer churn using an Artificial Neural Network (ANN). The dataset used contains customer information such as demographic details, account information, and usage patterns, which are used to build and train the ANN model.

## Project Structure
Customer_Churn_ANN.ipynb: The Jupyter notebook where the entire model development process is carried out, including data preprocessing, model building, training, and evaluation.
Installation
To run this project, ensure you have the following dependencies installed:

Python 3.x
Jupyter Notebook
TensorFlow
Keras
Pandas
NumPy
Matplotlib
Scikit-learn
You can install the dependencies using pip:


pip install tensorflow keras pandas numpy matplotlib scikit-learn
## How to Run
Clone the repository or download the .ipynb file.
Navigate to the project directory.
Open the Jupyter Notebook:

jupyter notebook Customer_Churn_ANN.ipynb
Run all the cells sequentially to preprocess the data, build the ANN model, and evaluate its performance.


Model Architecture
The ANN model built in this project has the following structure:

Input Layer: (11)
Hidden Layers: (100)
Hidden Layers: (100)
Hidden Layers: (10)
Output Layer: Single neuron with a sigmoid activation function to predict the probability of churn.
## Results
The model achieved an accuracy of 83% on the test set.

