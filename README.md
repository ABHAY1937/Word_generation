# Text Generation Web App with Flask and TensorFlow
![ezgif com-video-to-gif](https://github.com/ABHAY1937/Word_generation/assets/130343822/db4394f9-b101-42fa-90f8-1f8454591180)


This repository contains a simple web application built with Flask and TensorFlow for text generation. The application generates text based on the input provided by the user using a pre-trained RNN LSTM model.

## Requirements

To run this web application, you need to have the following dependencies installed:

- Python 3.x
- Flask
- NumPy
- TensorFlow
- pickle (for loading the tokenizer)
- (Other dependencies may be required based on your system configuration)

You can install the Python dependencies using pip:

```bash
pip install flask numpy tensorflow

Getting Started

    Clone this repository to your local machine:

bash

git clone <repository_url>
cd <repository_directory>

    Make sure you have the required model and tokenizer files. Update the file paths in the app.py file to match your system configuration.

    Start the Flask application:

bash

python app.py

    Open a web browser and go to http://localhost:5000 to access the text generation web app.

Usage

    Enter the starting word or phrase in the "Enter the First Word" input field.

    Enter the number of words you want to generate in the "Enter the Number of Words to Generate" input field.

    Click the "Predict" button.

    The predicted words will be displayed in the "Predicted words" section below.

Acknowledgments

    This project uses Flask for web application development.
    The text generation model is built using TensorFlow.
    The model's tokenizer is loaded from a pickle file.

