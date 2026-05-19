# Handwritten Digit Recognition Using ANN

## Overview
This project implements a handwritten digit recognition system using Artificial Neural Networks (ANN) trained on the MNIST dataset. The model classifies handwritten digit images (0–9) using TensorFlow and Keras.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

---

## Dataset
The project uses the MNIST handwritten digit dataset containing 70,000 grayscale images of digits from 0 to 9.

---

## Model Architecture
- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Dense Layer (32 neurons, ReLU)
- Output Layer (10 neurons, Softmax)

---

## Features
- Image preprocessing
- ANN model development
- Multiclass classification
- Model training and validation
- Prediction visualization
- Accuracy and loss analysis

---

## Model Performance
The model was trained using:
- Adam Optimizer
- Sparse Categorical Crossentropy Loss
- Accuracy Metric

---

## Results

### Loss Graph
<img width="692" height="522" alt="image" src="https://github.com/user-attachments/assets/7baa841e-00e4-4fa2-88b9-c81d43912d32" />


### Accuracy Graph
<img width="688" height="512" alt="image" src="https://github.com/user-attachments/assets/5b037b19-4202-45c0-bb1c-ac273a49e7a0" />


### Sample Prediction
<img width="578" height="583" alt="image" src="https://github.com/user-attachments/assets/3d1bd43d-fa74-4cb0-bb42-bdf5d1a3bd66" />
<img width="528" height="90" alt="image" src="https://github.com/user-attachments/assets/d5916398-fba4-42fa-8478-cdbdfda258f7" />

## Future Improvements
- CNN implementation
- Hyperparameter tuning
- Web app deployment using Streamlit
- Real-time digit recognition


## Author
Anita
