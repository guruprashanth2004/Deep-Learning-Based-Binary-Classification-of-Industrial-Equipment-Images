# **Industrial Equipment Defect Classifier**  
This project implements a convolutional neural network (CNN) to classify images of industrial equipment as either defective or non-defective. The project includes code for training, evaluating, and testing the model, along with instructions for using the model with uploaded images.

## **Features**
* Binary classification of industrial equipment images.
* Pre-trained CNN model for high accuracy.
* Evaluation with accuracy, precision, recall, and a confusion matrix.
* Test individual images for defect classification.

## **Dataset**
~~~md
dataset/
├── defective/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── non-defective/
    ├── image1.jpg
    ├── image2.jpg
    └── ...
~~~
## **Model Architecture**
The model is built using TensorFlow/Keras and consists of:
* Convolutional Layers: Extract features from images.
* Max Pooling Layers: Reduce dimensionality and computation.
* Fully Connected Layers: Make binary predictions.
## **Contributing**
Feel free to submit issues or pull requests. Contributions are welcome!



