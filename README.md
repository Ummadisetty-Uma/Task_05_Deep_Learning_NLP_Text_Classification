# Deep Learning Text Topic Classification

## Project Objective

The objective of this project is to build a Deep Learning based NLP model that classifies text documents into different topic categories.

## Dataset

The project uses the **20 Newsgroups dataset** provided through Scikit-learn. Four topic categories were selected:

* rec.sport.baseball
* sci.space
* comp.graphics
* talk.politics.misc

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Jupyter Notebook

## Methodology

The project follows these steps:

1. Load the 20 Newsgroups text dataset.
2. Explore and clean the text data.
3. Split the data into training, validation, and testing sets.
4. Convert text into numerical features using TF-IDF.
5. Build a multi-layer neural network using TensorFlow/Keras.
6. Apply Batch Normalization and Dropout.
7. Train the model using Early Stopping.
8. Plot training and validation accuracy and loss curves.
9. Evaluate the model using test accuracy, classification report, and confusion matrix.
10. Test the model on unseen text and display the predicted topic with confidence.

## Model Architecture

The neural network contains:

* Dense layer with 256 neurons
* Batch Normalization
* Dropout
* Dense layer with 128 neurons
* Batch Normalization
* Dropout
* Dense layer with 64 neurons
* Dropout
* Softmax output layer

## Results

The model was evaluated on unseen test data using:

* Test Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

Training and validation accuracy/loss curves were also plotted to observe model convergence.

## Sample Inference

The trained model was tested with new text samples that were not used during training. The model predicts the most likely topic and provides a confidence score for the prediction.

## Conclusion

This project demonstrates an end-to-end NLP text classification pipeline using TF-IDF and a Deep Learning neural network. It covers text preprocessing, feature extraction, model training, validation, evaluation, and prediction on unseen text.
