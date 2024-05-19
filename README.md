# Detección de Noticias Falsas

## Contenido

Este repositorio contiene un análisis y modelo de detección de noticias falsas. Se utilizó un archivo CSV que contiene información sobre artículos de noticias, incluyendo su título, autor, texto y una etiqueta que indica si el artículo es potencialmente no fiable. El análisis y el modelo se realizaron utilizando Python y varias bibliotecas de procesamiento de texto y aprendizaje automático.

- **Data:** [Archivo CSV](https://www.kaggle.com/competitions/fake-news/data?select=train.csv) con los datos originales de artículos de noticias.
- **Notebooks:** Carpeta que contiene el Jupyter Notebook utilizado para realizar el análisis y el desarrollo del modelo de detección de noticias falsas.
- **README.md:** Este archivo README que proporciona una descripción general del proyecto y su contenido.

## Análisis Realizado

Se cargaron, limpiaron y prepararon los datos utilizando Pandas y NLTK. Posteriormente, se creó y se entrenó un modelo de regresión logística utilizando la librería Scikit-Learn. Finalmente, se analizaron los resultados del modelo, evaluando su precisión, matriz de confusión e informe de clasificación.

## Objetivo

El objetivo de este proyecto es desarrollar un modelo de aprendizaje automático capaz de detectar noticias falsas utilizando técnicas de procesamiento de lenguaje natural (NLP) y un modelo de regresión logística. El modelo se evalúa en términos de precisión y otras métricas de rendimiento para determinar su efectividad en la detección de noticias potencialmente no fiables.

## Tecnologías Utilizadas

- Python: Pandas, NLTK, Scikit-Learn
- Jupyter Notebooks

## Conclusión

El modelo de detección de noticias falsas logró una precisión del 95%, lo que demuestra su efectividad en la clasificación de artículos de noticias como falsos o no falsos.

## Descripción del Dataset

- `train.csv`: Un conjunto de datos de entrenamiento completo con los siguientes atributos:
  - `id`: ID único para un artículo de noticias
  - `title`: El título de un artículo de noticias
  - `author`: Autor del artículo de noticias
  - `text`: El texto del artículo; podría estar incompleto
  - `label`: Una etiqueta que marca el artículo como potencialmente no fiable
