# Práctica Final NLP - Análisis de Sentimiento en Reseñas de Amazon Digital Music

## Objetivo del proyecto

Este proyecto consiste en desarrollar un flujo completo de procesamiento de lenguaje natural (NLP) aplicado al análisis de sentimiento. El objetivo principal es entrenar y comparar varios modelos de clasificación para predecir el sentimiento (positivo o negativo) de reseñas de productos de música digital en Amazon. Se incluyen exploración descriptiva y limpieza de datos, preprocesado de texto (minúsculas, eliminación de puntuación, lematización, stopwords), vectorización mediante Bag-of-Words, entrenamiento de modelos clásicos y redes neuronales, evaluación comparativa de métricas de rendimiento y visualización de embeddings y clusters.

## Estructura del repositorio

- practica_NLP_Keepcoding.ipynb: Notebook principal con todo el flujo de trabajo.
- reviews_Digital_Music_5.json.gz: Archivo de datos comprimido que contiene las reseñas originales.
- requirements.txt: Listado de dependencias necesarias para ejecutar el notebook.
- README.md: Este archivo.
- Practica final NLP.pdf: Exportación en PDF del notebook con los resultados obtenidos.

## Requisitos previos

Para ejecutar el notebook en un entorno limpio (por ejemplo, Google Colab), es necesario instalar las dependencias indicadas. Se recomienda utilizar Python >=3.8.

Instalación de dependencias:

```bash
pip install -r requirements.txt
```

El archivo requirements.txt incluye paquetes como:

- pandas
- numpy
- scikit-learn
- gensim
- spacy
- nltk
- matplotlib
- seaborn
- wordcloud
- adjustText

## Ejecución en Google Colab

Si utilizas Google Colab, sigue estos pasos:

1. Sube los archivos necesarios:
   - reviews_Digital_Music_5.json.gz
   - requirements.txt
   - El notebook practica_NLP_Keepcoding.ipynb

2. Instala las dependencias ejecutando en una celda:

```python
!pip install -r requirements.txt
```

3. Verifica que el dataset esté en el mismo directorio de trabajo. El notebook espera que reviews_Digital_Music_5.json.gz se encuentre en el directorio raíz.

## Notas importantes

- El dataset contiene aproximadamente 65,000 reseñas.
- Algunas operaciones, como el preprocesado de texto y el entrenamiento de Word2Vec, pueden requerir varios minutos de procesamiento.
- Se recomienda usar un entorno con CPU adecuada.

## Contacto

Proyecto académico realizado como parte de la práctica final de NLP por el Ing. Darío F. Tomatis. mail: dftomatis@gmail.com

