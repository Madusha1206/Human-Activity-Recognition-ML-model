# Human Activity Recognition Using 1D CNN

A deep learning-based **Human Activity Recognition (HAR)** system developed using a **1D Convolutional Neural Network (1D CNN)** to classify human activities from wearable accelerometer sensor data.

## Activities

The model classifies six activities:

* Cycling
* Pushup
* Running
* Squat
* Table Tennis
* Walking

The dataset contains readings from **5 wearable accelerometers**, each providing X, Y, and Z-axis measurements, giving **15 input features**.

## Model

The accelerometer data was cleaned, normalized, and converted into time-series sequences using overlapping sliding windows. A **1D CNN** was then used to extract temporal features and classify the activities.

**Model performance:**

* Full 5-sensor model: **93.8% accuracy**
* Best 2-sensor combination (S2 + S5): **95.5% accuracy**

## Technologies

`Python` • `TensorFlow/Keras` • `1D CNN` • `Scikit-learn` • `Pandas` • `NumPy` • `Google Colab`

## Demo

🤗 **Live Model:**
https://huggingface.co/spaces/Madusha456/HAR_5198

🎥 **Demo Video:**
https://youtu.be/mxZN5oMW_wg
