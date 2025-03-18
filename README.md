# 📊 Entrega 4: K-Nearest Neighbors (KNN)

## 🏫 Universidad del Valle de Guatemala - Campus Central  
**Curso:** Minería de Datos (CC3074) - Sección 10  
**Proyecto:** Proyecto #2  
**Grupo:** #1  

## 👥 Integrantes del Grupo #1  
- **Pablo Daniel Barillas Moreno** - *Carné No. 22193*  
- **Mathew Cordero Aquino** - *Carné No. 22982*  

---

## 📌 Descripción del Proyecto  
Este proyecto corresponde a la **Entrega 4 del Proyecto #2** dentro del curso de **Minería de Datos**.  
En esta etapa, se desarrolló un modelo basado en **K-Nearest Neighbors (KNN)** para la predicción y clasificación de precios de viviendas utilizando el conjunto de datos de Kaggle *"House Prices: Advanced Regression Techniques"*.  

**Objetivo principal:**  
Construir modelos de **regresión y clasificación** utilizando **KNN** y comparar su desempeño con modelos previos de regresión lineal, árboles de decisión, Random Forest y Naive Bayes.

---

## 📊 Metodología Aplicada  

1. **Preprocesamiento de Datos**  
   - Limpieza y manejo de valores faltantes.  
   - Conversión de variables categóricas en factores.  
   - Normalización de variables numéricas para mejorar el rendimiento de KNN.  

2. **Modelado con KNN**  
   - Creación de un **modelo de regresión** para predecir `SalePrice`.  
   - Creación de un **modelo de clasificación** con las categorías (`Económica`, `Intermedia`, `Cara`).  
   - Ajuste del valor óptimo de **k** mediante validación cruzada.  

3. **Evaluación del Modelo**  
   - **Regresión:** Cálculo de **Error Cuadrático Medio (MSE), Raíz del Error Cuadrático Medio (RMSE), R²**.  
   - **Clasificación:** Construcción de **matriz de confusión**, análisis de **precisión, recall y F1-score**.  
   - Comparación del desempeño de **KNN vs Modelos anteriores** (Regresión Lineal, Árboles de Decisión, Random Forest, Naive Bayes).  

4. **Optimización y Validación**  
   - Aplicación de **validación cruzada** para encontrar el mejor valor de **k**.  
   - Evaluación de diferentes métricas de distancia (Euclidiana, Manhattan).  

---

## 🛠 Tecnologías Utilizadas  

- **Lenguaje utilizado:** R  
- **Plataforma:** RStudio  
- **Paquetes utilizados:** `class`, `caret`, `tidyverse`, `ggplot2`, `kknn`  
- **Control de Versiones:** GitHub  

---

## 📢 Resultados Destacados  

✔️ Se implementó un **modelo de KNN** para predecir precios de viviendas y clasificarlas en rangos de precio.  
✔️ Se compararon los resultados con **modelos previos de regresión lineal, árboles de decisión, Random Forest y Naive Bayes**.  
✔️ Se optimizó el modelo con **validación cruzada y ajuste de hiperparámetros**.  
✔️ Se evaluó la precisión del modelo mediante **métricas de error, matriz de confusión y F1-score**.  
✔️ Se analizaron los **efectos del número de vecinos (k) en el rendimiento del modelo**.  

---
