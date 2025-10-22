# Handwritten Digit Recognition

## Overview

Handwritten Digit Recognition is a browser-based application for recognizing handwritten digits (0-9). This project uses a machine learning model originally trained with PyTorch, converted to JavaScript format for browser execution. The application utilizes arrays and matrices to represent biases and weights, enabling quick and efficient digit recognition.

## How It Works

The core of this application is a neural network, a computational model inspired by the human brain. It consists of layers of interconnected nodes (neurons) that process input data and make predictions. The model predicts handwritten digits from 0 to 9 using pre-trained weights and biases.

## Live Demo

[Try the application online](https://hoffhannisyan.github.io/handwritten-digit-recognition/)

Draw any digit (0-9) on the canvas and see the neural network predict it in real-time!

## Running the Project

To run the Handwritten Digit Recognition application:

1. Clone the project from the GitHub repository
2. Ensure you have Node.js installed on your machine
3. Navigate to the project directory in your terminal
4. Run the project using `npm run start` or `node app.js`
5. Open your web browser and navigate to `http://localhost:8080`

You'll see a canvas where you can draw digits using your mouse or touchscreen. The prediction chart next to the canvas will display the recognized digit, with column heights representing the model's confidence in its prediction.

## Features

- Real-time digit recognition
- Interactive drawing canvas
- Visual confidence display for predictions
- Runs entirely in the browser

## Technology Stack

- JavaScript/HTML5 Canvas
- Neural Network (PyTorch → JavaScript)
- Node.js (for local server)
