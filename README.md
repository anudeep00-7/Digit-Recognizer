# Handwritten Digit Recognizer

A full stack computer vision application that recognizes handwritten digits using a Convolutional Neural Network trained on the MNIST dataset.

### Features
* Custom CNN built and trained with PyTorch
* FastAPI backend for fast inference handling
* Interactive HTML5 Canvas frontend for user input
* Dynamic image preprocessing pipeline

### Tech Stack
* Python
* PyTorch
* FastAPI
* Uvicorn
* HTML5 / JavaScript / CSS

### Project Setup

1. Clone the repository and navigate to the project directory.
2. Install the required backend dependencies.
   `pip install -r backend/requirements.txt`

### Running the Application

1. Open a terminal and navigate to the backend directory.
2. Generate the model weights by running the training script.
   `python train.py`
3. Once the `mnist_cnn.pt` file is generated, start the server.
   `python app.py`
4. Open the `frontend/index.html` file in any web browser to interact with the application.
