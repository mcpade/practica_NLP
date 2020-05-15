# Práctica: Módulo NLP - Bootcamp KeepCoding - BIG DATA & MACHINE LEARNING

# NLP

En este práctica se implementan y comparan varios modelos de Sentiment Analysis utilizando algoritmos de Machine Learning y 
arquitecturas Deep Learning. Además se utiliza la técnica Topic Modeling para el análisis de Tweets y la técnica Language 
Modeling para la generación de Tweets. 

El código está desarrollado en Python.

Conceptos tratados en esta práctica:

- Librerías **numpy**, **pandas**, **re**, **spacy**, **Sklearn**, **Keras**, **gensim**, **pyLDAvis** de Python 
- Preprocesado de datos: Uso de expresiones regulares, conversión a minúsculas, eliminación de signos de puntuación, Lemmas,
Stopword
- Modelos para Sentiment Analysis con algoritmos de Machine Learning. Pipeline para selección de los mejores parámetros

      - Naive Bayes
      
      - SVM - Support Vector Machines
      
- Modelos para Sentiment Analysis con algoritmos de DeepLearning. Word Embeddings

      - Preprocesado: Tokenizado y vocabulario
      
      - Padding
      
      - Modelo Deep Averaging Networks - DAN
      
      - Modelo Convolutional Neural Networks para Texto - CNN
      
      - Modelo Recurrent Neural Network para texto - RNN
      
      - Modelo BiLSTM
      
      - Modelo BiLSTM con vectores pre-entrenados de Glove para la capa embeddings
- Topic Modeling

      - Algoritmo Latent Dirichlet Allocation - LDA
      
      - Visualización del modelo - pyLDAvis
      
- Language Modeling con arquitectura RNN

## Enunciado

1.- Machine Learning vs Deep Learning 

1.1. Implementación de un modelo de Sentiment Analysis con algún algoritmo de Machine Learning Clásico.

1.2. Implementación de un modelo de Sentiment Analysis con alguna arquitectura de Deep Learning.

1.3. Breve Comparación de resultados. Confusion Matrix.

2.- Hacer Analysis de los tweets del segundo dataset. Que temas aparecen? ¿Como se representan estos temas? ¿De que hablan unos y otros?

3.- Escoged a uno de los dos presidentes, y escribid tweets como ellos, usando un Modelo Generativo.

## Conjunto de datos

Para el primer ejercicio se utiliza el dataset **"train_sentiment.csv"** y para los ejercicios 2 y 3 se utiliza el datset **"dataset_2.json"**. Ambos están en la carpeta **data** de este repositorio


