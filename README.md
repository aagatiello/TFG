# TFG

## :round_pushpin: Objetivo
Análisis de sentimiento en textos largos utilizando reseñas de Amazon para saber si expresan un sentimiento positivo, negativo o neutro.

## :bookmark_tabs: Contenido
1) EDA: análisis exploratorio de los datos
2) Features: preprocesamiento y análisis de las características
3) Train test: división aleatoria y validación cruzada

Modelos de clasificación:

4) Multinomial Naive Bayes
5) Support Vector Machine
6) Regresión Logística

Ajuste de hiperparámetros:

- GridSearchCV
- Hyperparameters_MNBayes
- Hyperparameters_SVM
- Hyperparameters_LogisticRegression

Comparación demo:

- Sentences_TextBlob

**!** Como los gráficos generados por plotly son dinámicos no es posible ver los resultados en la vista previa, para ello se puede consultar el PDF del notebook correspondiente.

## :paperclips: Pre-requisitos 
Para poder ejecutar el Notebook revisar los requerimientos de las librerias y sus versiones en `requirements.txt`.

```
imbalanced_learn == 0.9.1
matplotlib == 3.5.1
nltk == 3.7
numpy == 1.21.5
pandas == 1.4.3
plotly == 5.10.0
scikit_learn == 1.1.2
scipy == 1.8.0
seaborn == 0.11.2
textblob == 0.17.1
wordcloud == 1.8.2.2
```
