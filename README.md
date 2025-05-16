# Handwritten Digit Recognition using CNN and MNIST

This project is a **handwritten digit recognition system** that uses a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**. It allows users to **draw digits (0–9)** in a custom drawing window, and the trained model will predict the digit in real-time.

## Features

- Uses TensorFlow/Keras and OpenCV.
- Trained on 60,000 MNIST digit images.
- Interactive digit drawing pad using OpenCV.
- Real-time prediction of handwritten digits (0 to 9).

## Requirements

- Python 3.10
- TensorFlow
- NumPy
- Pillow
- OpenCV (cv2)
- JupyterLab / Notebook

Install dependencies with:
```bash
pip install -r requirements.txt
```

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/digit_recognition_project.git
cd digit_recognition_project
```

2. Launch JupyterLab or Notebook:
```bash
jupyter lab
# or
jupyter notebook
```

3. Open `digit_recognition.ipynb` and run all cells.

## Screenshots

*(Add a screenshot of the drawing window and prediction result here if you want.)*

## Project Structure

```
digit_recognition_project/
│
├── digit_recognition.ipynb   # Main notebook
├── README.md                 # Project description
└── requirements.txt          # Required libraries
```

## License

This project is for educational purposes.