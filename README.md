# Clasificacion-Imagenes-con-CNNs-

Este proyecto implementa una **Red Neuronal Convolucional (CNN)** en **TensorFlow/Keras** para clasificar imágenes del dataset **CIFAR-10**, que contiene 10 categorías como aviones, coches, gatos, perros, etc.

## Dataset
El dataset CIFAR-10 tiene 60,000 imágenes en 10 clases:
- Avión
- Automóvil
- Pájaro
- Gato
- Ciervo
- Perro
- Rana
- Caballo
- Barco
- Camión

## Modelo CNN
La red neuronal tiene las siguientes capas:
- **Conv2D + ReLU** (extracción de características)
- **MaxPooling2D** (reducción de dimensiones)
- **Fully Connected (Dense)** (clasificación final)

## Resultados
La CNN alcanzó una precisión de **71%** en el conjunto de prueba.
