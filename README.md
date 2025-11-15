# Evaluación 4 Machine Learning  
### Análisis de Sentimientos (Amazon Fine Food Reviews)  
### y Clustering de Clientes (Mall Customers Dataset)

---

## Descripción General

Este repositorio contiene el desarrollo de los 2 ejercicios propuestos.  
Aquí se abordan tanto técnicas supervisadas (clasificación) como no supervisadas (clustering), utilizando datasets reales y aplicando procesos de análisis, modelado y visualización de datos.

Los ejercicios incluidos son:

- **Ejercicio 3:** Clasificación de sentimientos en reseñas de Amazon.
- **Ejercicio 4:** Segmentación de clientes mediante algoritmos de clustering.

---

## Video de Presentación del Proyecto

En el siguiente enlace se encuentra el vídeo sobre la explicación de los ejercicios:

**https://drive.google.com/file/d/1eTyOB9JOi-bsUhPaZP7w8-9zq2j-v9bZ/view?usp=drive_link**

---

## Ejercicio 3 – Análisis de Sentimientos

### Objetivo
Clasificar reseñas de productos como positivas o negativas a partir del texto, aplicando técnicas de procesamiento de lenguaje natural.

### Archivos relacionados
- `ejercicio3/Ejercicio3_AmazonSentiment.ipynb`
- `ejercicio3/ejercicio3.py`

### Técnicas utilizadas
- Limpieza de texto  
- Eliminación de stopwords  
- Tokenización  
- Vectorización TF-IDF  
- Modelos: Naive Bayes, Logistic Regression, SVM  
- Reducción de dimensionalidad: t-SNE, SVD  
- Métricas: Accuracy, F1-score, Matriz de confusión, ROC-AUC  

### Resultados principales
- **SVM** obtuvo el mejor desempeño (F1 > 0.96).  
- Las curvas ROC muestran excelente capacidad de separación.  
- t-SNE revela separación parcial entre sentimientos.  
- El dataset presenta desafíos por ambigüedad y sarcasmo natural del lenguaje humano.

---

## Ejercicio 4 – Clustering de Clientes (Mall Customers)

### Objetivo
Identificar segmentos de clientes basados en características de consumo, para comprender patrones de comportamiento en un centro comercial.

### Archivos relacionados
- `ejercicio4/Ejercicio4_MallCustomersClustering.ipynb`
- `ejercicio4/ejercicio4.py`

### Técnicas utilizadas
- Normalización de variables  
- Algoritmos: K-Means, DBSCAN, Clustering Jerárquico  
- Visualizaciones: Elbow Method, Silhouette Score, PCA  
- Dendrogramas para estructura jerárquica  

### Resultados principales
- **K-Means** obtuvo la mejor segmentación del dataset (k=5).  
- DBSCAN detectó varios puntos atípicos pero no formó clústeres claros.  
- PCA permitió visualizar la separación entre grupos.  
- Los clústeres detectados representan distintos perfiles de consumo y poder adquisitivo.

---

## Estructura del repositorio

Evaluacion4/
├── ejercicio3/
│ ├── Ejercicio3_AmazonSentiment.ipynb
│ └── ejercicio3.py
├── ejercicio4/
│ ├── Ejercicio4_MallCustomersClustering.ipynb
│ └── ejercicio4.py
└── README.md