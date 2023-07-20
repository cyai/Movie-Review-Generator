# Movie Review Sentiment Analysis

This machine learning project is designed to determine the performance of a movie based on its review sentiment. The project uses a recurrent neural network (RNN) with Long Short-Term Memory (LSTM) layers to analyze movie reviews and predict their sentiments.

## Introduction

Sentiment analysis, also known as opinion mining, is a Natural Language Processing (NLP) technique used to determine the sentiment or emotion expressed in a piece of text. In this project, we focus on sentiment analysis for movie reviews, where we aim to classify whether a review is positive or negative.

## Data

The dataset used in this project is the IMDB movie reviews dataset, which consists of movie reviews along with their corresponding sentiment labels (positive or negative). The dataset is loaded using the Keras library, which provides convenient functions for preprocessing text data.

## Code Structure

The code in the Jupyter Notebook is structured into different sections:

1. **Data Preparation**: The dataset is loaded and preprocessed to convert the text reviews into numerical sequences using word embeddings.

2. **Model Architecture**: The LSTM-based RNN model is defined using the Keras Sequential API. The model summary is displayed to show the layers and their output shapes.

3. **Training the Model**: The model is compiled with the appropriate loss function and optimizer, and then trained using the training data. The training history is stored for further analysis.

4. **Evaluation**: The model's performance is evaluated on the test data to determine its accuracy.

5. **Prediction**: The user can enter their own movie review, and the trained model will predict its sentiment (positive or negative).

## How to Use the Code

1. Clone or download the repository to your local machine.

2. Install the required libraries (Keras, TensorFlow, and NumPy).

3. Open the Jupyter Notebook `Natural_Language_Processing_with_RNN's.ipynb`.

4. Follow the code step-by-step to understand how the model is constructed, trained, and evaluated.

5. To make your own prediction, run the last code cell and enter your movie review when prompted.

## Dependencies

To run this code, you need the following dependencies:

- Python 3.9.0
- Jupyter Notebook
- TensorFlow 2.x
- Keras
- NumPy

## Credits

The IMDB dataset and relevant libraries used in this project are part of the Keras library and TensorFlow ecosystem. The model architecture is inspired by research in Natural Language Processing and Sentiment Analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note**: The performance of the model might vary depending on the complexity of the movie reviews and the size of the dataset used for training. It is recommended to experiment with different hyperparameters and architectures to optimize the model's performance for specific use cases.

Please feel free to reach out for any questions or feedback regarding the project! Happy coding!
