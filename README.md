# Natural Language Processing (ECI 2019)

El ejercicio completo se encuentra en el siguiente link: https://www.kaggle.com/c/eci2019nlp

### Resumen del ejercicio
Uno de los datasets más famosos de Natural Language Inference es SNLI. En esta tarea se debe responder, dadas dos frases A y B, si B es implicación de A ("entailment"), B es contradictorio con A ("contradiction") o si lo que enuncia B es neutral respecto de A ("neutral"). Se dice que A es la premisa y B es la hipótesis.
En Gururangan et al., 2018 mostraron que este dataset tiene algunos sesgos, provocados por ejemplo por las heurísticas que tienen los humanos para generar estos pares de frases (A, B). Para ello, desarrollaron un modelo que aún sin observar la premisa A pudiera clasificar el par (A, B) en alguna de las tres clases del dataset.
En este trabajo práctico intentaremos predecir a qué clase pertenece cada una de las hipótesis sin observar la premisa. La idea es replicar los resultados publicados en Gururangan et al., 2018 y mejorarlos si es posible utilizando clasificadores más complejos.
