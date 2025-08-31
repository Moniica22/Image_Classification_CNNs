# Image Classification with CNNs

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to classify images from the **CIFAR-10** dataset. The model learns to distinguish between 10 object categories such as airplanes, cars, cats, dogs, and more.


## Dataset
The [CIFAR-10 dataset] contains 60,000 images divided into 10 classes (6,000 images per class):
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck


## CNN Architecture

The CNN architecture used in this project includes:
- `Conv2D` layers with ReLU activation (feature extraction)
- `MaxPooling2D` layers (downsampling)
- `Dense` fully connected layers (final classification)


## Results
After training, the CNN achieved an accuracy of **71%** on the test dataset.

## Ejecution
```
# Clone the repository
git clone https://github.com/Moniica22/Clasificacion-Imagenes-con-CNNs-.git
cd Clasificacion-Imagenes-con-CNNs-
```

# Install dependencies
```
pip install -r Requirements.txt
```

# Run the training notebook
```
jupyter notebook CIFAR-10.ipynb
```
