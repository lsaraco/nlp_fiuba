# NLP (Procesamiento del lenguje natural) - FIUBA


- En este repositorio se almacenarán los desafíos desarrollados durante el curso de NLP en la FIUBA.
- Autor: Leandro Saraco
- Fecha: Septiembre-Octubre 2024


## Desafío 1 - Vectorización:

<img src="https://raw.githubusercontent.com/lsaraco/nlp_fiuba/refs/heads/main/doc/imgs/bow.webp" width="40%">


1. Vectorización de documentos utilizando algoritmos del tipo BOW.
1. Medir similitud de documentos utilizando similitud coseno.
1. Clasificar documentos utilizando Naive Bayes (MultinomialNB y ComplementNB).
1. Obtener palabras similares mediante similitud coseno.

Link: [https://github.com/lsaraco/nlp_fiuba/Desafio_1](https://github.com/lsaraco/nlp_fiuba/tree/main/Desafio_1)


## Desafío 2 - Word embeddings:

<img src="https://raw.githubusercontent.com/lsaraco/nlp_fiuba/refs/heads/main/doc/imgs/tokenizer.webp" width="40%">

1. Tokenización usando funciones de preprocesamiento de texto de Keras.
1. Word embeddings usando modelos word2vec en Gensim.
1. Análisis de relación de términos a partir de embeddings.
1. Tests de analogías.
1. Proyección de embeddings en 2D y 3D para su visualización.
1. El desarrollo de este trabajo se realiza a partir de un dataset de recetas extraidas de Reddit.

Link: [https://github.com/lsaraco/nlp_fiuba/Desafio_2](https://github.com/lsaraco/nlp_fiuba/tree/main/Desafio_2)


## Desafío 3 - Modelos de lenguaje:

<img src="https://raw.githubusercontent.com/lsaraco/nlp_fiuba/refs/heads/main/doc/imgs/language_model.webp" width="40%">

1. Modelo de lenguaje para predecir palabras y generar secuencias. [Notebook](https://github.com/lsaraco/nlp_fiuba/blob/main/Desafio_3/Palabras/Modelo_prediccion_palabras.ipynb)
1. Modelo de lenguaje para predecir caracteres y generar secuencias. [Notebook](https://github.com/lsaraco/nlp_fiuba/blob/main/Desafio_3/Caracteres/modelo_prediccion_caracteres.ipynb)
1. Utilizando diferentes arquitecturas de redes neuronales recurrentes: simpleRNN, LSTM y GRU.

Link: [https://github.com/lsaraco/nlp_fiuba/Desafio_3](https://github.com/lsaraco/nlp_fiuba/tree/main/Desafio_3)


## Desafío 4 - QA Chatbot - Seq2Seq:

<img src="https://raw.githubusercontent.com/lsaraco/nlp_fiuba/refs/heads/main/doc/imgs/seq2seq.webp" width="40%">

1. Chatbot de preguntas y respuestas. [Dataset](http://convai.io/data/)
1. Utilizando redes recurrentes LSTM y capas de embeddings (pre-entrenados de FastText).
1. Arquitectura encoder-decoder.
  1. Modelo para entrenamiento.
  1. Modelo autoregresivo para inferencia.

Link: [https://github.com/lsaraco/nlp_fiuba/Desafio_4](https://github.com/lsaraco/nlp_fiuba/tree/main/Desafio_4)

## Desafío 5 - Sentiment analysis usando BERT

<img src="https://raw.githubusercontent.com/lsaraco/nlp_fiuba/refs/heads/main/doc/imgs/app_review.webp" width="40%">

1. Sentiment analysis utilizando pooled_output de BERT.
1. Uso de transfer learning.
1. Clasificación con capas densas a partir de pooled_output
  1. Comparación de dos modelos diferentes.

Link: [https://github.com/lsaraco/nlp_fiuba/Desafio_5](https://github.com/lsaraco/nlp_fiuba/tree/main/Desafio_5)
