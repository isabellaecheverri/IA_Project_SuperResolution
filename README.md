# 🕹️ Super Resolution AI for Video Games

Este repositorio contiene un proyecto de super-resolución de imágenes utilizando modelos de aprendizaje profundo. Se enfoca en mejorar imágenes de videojuegos, transformándolas desde una baja resolución (LR) a una alta resolución (HR).

## 📌 Descripción

La super-resolución es una técnica de visión por computadora que permite aumentar la calidad de imágenes de baja resolución. En este proyecto, se emplea un modelo de super-resolución basado en PyTorch y TorchSR sobre un dataset de imágenes LR-HR provenientes de videojuegos.

## 🧪 Dataset

El dataset utilizado es **super-resolution-in-video-games** disponible en Kaggle. Contiene pares de imágenes de entrenamiento:

- `/train/lr`: Imágenes en baja resolución.
- `/train/hr`: Las mismas imágenes en alta resolución.

## 📂 Estructura del proyecto

```
.
├── super-resolution-ai-project.ipynb  # Notebook principal con visualizaciones y predicciones
├── README.md                          # Este archivo
```

## 🚀 Cómo usar este repositorio

1. **Instala las dependencias**

```bash
pip install torch torchsr torchvision tqdm opencv-python matplotlib
```

2. **Ejecuta el notebook**

Puedes correr el notebook directamente en [Kaggle](https://www.kaggle.com/) o en tu entorno local si tienes el dataset.

```bash
jupyter notebook super-resolution-ai-project.ipynb
```

3. **Visualiza resultados**

El notebook incluye visualizaciones comparativas entre imágenes originales (LR), imágenes de alta resolución reales (HR) y las generadas por el modelo.

## 🧠 Modelo utilizado

- **TorchSR**: Se utiliza un modelo de super-resolución preentrenado compatible con PyTorch.
- **OpenCV y Matplotlib**: Para visualización de resultados.

## 📊 Resultados

El notebook muestra ejemplos claros de mejora visual en las imágenes procesadas, comparando la entrada (LR), la salida del modelo y la imagen HR original.

## ✍️ Autor

Felipe Henao, Isabella Echeverry, Martin Ospina, Miguel Chacón.
