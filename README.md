# Práctica: Módulo NLP - Bootcamp KeepCoding - BIG DATA & MACHINE LEARNING

# NLP

En este práctica se implentan y comparan varios modelos de Sentiment Analysis utilizando algoritmos de Machine Learning y 
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
