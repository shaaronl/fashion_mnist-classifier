# Clothing Classifier 🥼

This project is a simple clothing classifier web application built using Streamlit and TensorFlow. It leverages a pre-trained Fashion MNIST model to classify images of clothing items. The application provides real-time predictions along with a bar chart visualizing the confidence levels for each class.

## Features

- Upload images of clothing items in JPG, JPEG, or PNG format.
- Classify the uploaded image using a pre-trained Fashion MNIST model.
- Display the predicted clothing category.
- Visualize the confidence levels of all possible classes in a bar chart.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- Streamlit
- Pandas
- PIL (Pillow)
- Numpy


### Running the App

1. **Navigate to the project directory.**

2. **Start the Streamlit app:**

    ```bash
    streamlit run main.py
    ```

3. **Open the application in your web browser at `http://localhost:8501`.**

### Usage

- Upload an image of a clothing item using the file uploader.
- Click the "Classify" button to get the predicted category.
- View the prediction along with a bar chart showing the confidence levels for each class.

### File Structure

- `main.py`: The main Streamlit application file.
- `trained_model/`: Directory containing the pre-trained model file (`trained_fashion_mnist_model.h5`).
- `requirements.txt`: List of dependencies (if applicable).
