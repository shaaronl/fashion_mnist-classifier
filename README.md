# Clothing Classifier 🥼

This project is a simple clothing classifier web application built using Streamlit and TensorFlow. It leverages a custom-trained Fashion MNIST model to classify images of clothing items. The application provides real-time predictions along with a bar chart visualizing the confidence levels for each class.

## Features

- Upload images of clothing items in JPG, JPEG, or PNG format.
- Classify the uploaded image using a custom-trained Fashion MNIST model.
- Display the predicted clothing category.
- Visualize the confidence levels of all possible classes in a bar chart.

## Fashion MNIST Categories

The **Fashion MNIST** dataset contains 60,000 training images and 10,000 testing images, each belonging to one of the 10 clothing categories. These are:

1. **T-shirt/top**
2. **Trouser**
3. **Pullover**
4. **Dress**
5. **Coat**
6. **Sandal**
7. **Shirt**
8. **Sneaker**
9. **Bag**
10. **Ankle boot**

These categories represent the different types of clothing that the model has been trained to recognize.

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

   ```bash
   cd fashion_mnist-classifier/app
   ```

2. **Install dependencies:**

   ```bash
   pip install streamlit
   ```

3. **Start the Streamlit app:**

   ```bash
   streamlit run main.py
   ```

4. **Open the application in your web browser at `http://localhost:8501`.**

### Usage

- Upload an image of a clothing item using the file uploader.
- Click the "Classify" button to get the predicted category.
- View the prediction along with a bar chart showing the confidence levels for each class.

### File Structure

- `main.py`: The main Streamlit application file.
- `trained_model/`: Directory containing the custom-trained model file (`trained_fashion_mnist_model.h5`).
