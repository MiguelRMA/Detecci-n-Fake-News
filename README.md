# 📰 Detección de Fake News usando NLP (ELMo vs TF-IDF)

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Este repositorio contiene un flujo de trabajo en Procesamiento de Lenguaje Natural (PLN) para la clasificación y detección automática de noticias falsas, comparando enfoques tradicionales con embeddings contextuales de aprendizaje profundo.

## 📌 Características del Proyecto
* **Dataset:** Integración y limpieza de noticias reales (`True.csv`) y falsas (`Fake.csv`)[cite: 11].
* **Preprocesamiento:** Limpieza de texto, tokenización y combinación de título con cuerpo del artículo[cite: 11].
* **Modelos Evaluados:**
  * **Línea base:** Representación TF-IDF con clasificadores clásicos[cite: 11].
  * **Deep Learning:** Embeddings contextuales **ELMo** a través de TensorFlow Hub[cite: 11].

## 📊 Dataset
El dataset utilizado proviene de Kaggle y consta de artículos etiquetados:
* `1`: Noticias verdaderas (fuente: Reuters)[cite: 11].
* `0`: Noticias falsas (fuente: PolitiFact)[cite: 11].

## 🛠️ Tecnologías y Librerías
* Python
* Pandas & NumPy (Manipulación de datos)
* NLTK & Scikit-Learn (PLN tradicional)
* TensorFlow / TensorFlow Hub (ELMo)
* Matplotlib & Seaborn (Visualización)

## 🚀 Cómo Ejecutar el Proyecto
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
