# Cats vs Dogs Image Classification

This project demonstrates image classification using TensorFlow with two approaches:
1. A custom CNN model built from scratch
2. Transfer learning using the convolutional base from the trained model

## Dataset
Microsoft's Cats vs Dogs dataset from Kaggle (https://www.microsoft.com/en-us/download/details.aspx?id=54765)

## Requirements
- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib

## Usage
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook main.ipynb`

The notebook will:
- Download and preprocess the dataset
- Train a custom CNN model
- Implement transfer learning using the CNN base
- Visualize training/validation accuracy

## Results
The project compares the performance of:
- Custom CNN (10 epochs)
- Transfer learning model (10 additional epochs)

Accuracy metrics are plotted for both approaches.

Additional Files to Include (if running in a virtual environment):

1. `requirements.txt` (for pip installations):

```
tensorflow>=2.0
numpy
matplotlib
jupyter
```
