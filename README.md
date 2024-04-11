# Generative Adversarial Network (GAN) for Image Generation
Este repositorio contiene una implementación de una Generative Adversarial Network (GAN) utilizando TensorFlow/Keras para generar imágenes realistas a partir de un conjunto de datos de caras de personajes de Los Simpsons. La GAN consta de un discriminador y un generador, entrenados de manera adversarial para mejorar la calidad de las imágenes generadas.

Características
Utiliza una arquitectura de red neuronal convolucional (CNN) profunda (DC-GAN) para generar imágenes realistas.
Incluye un monitor personalizado (GANMonitor) que guarda imágenes generadas al final de cada época durante el entrenamiento.
Se utiliza la función de pérdida Binary Crossentropy para optimizar la capacidad discriminatoria de la red.
Se proporciona un script para cargar y preprocesar un conjunto de datos de caras de Los Simpsons.
