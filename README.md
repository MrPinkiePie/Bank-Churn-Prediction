# 🏦 Predicción de Fuga de Clientes (Bank Churn Prediction)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RJFpbTW81iHQa-eRUehy-33YRwP6AwUy?usp=sharing)

### 📋 Descripción del Proyecto
Este proyecto busca resolver un problema crítico en la banca: la pérdida de clientes. Utilizando un dataset histórico, desarrollé un modelo de Machine Learning capaz de identificar qué clientes tienen mayor probabilidad de abandonar la entidad, permitiendo tomar acciones preventivas.

### 🛠️ Tecnologías y Herramientas
* **Lenguaje:** Python 🐍
* **Librerías:** Pandas, Scikit-learn, XGBoost, Imblearn, SHAP, Matplotlib/Seaborn.
* **Metodología:** Análisis Exploratorio (EDA), Ingeniería de Características, Balanceo de Clases (Undersampling/Oversampling).

### 📊 Resultados Clave
El modelo final (basado en **XGBoost** con **Undersampling**) fue optimizado para maximizar la detección de fugas:

| Métrica | Resultado | Interpretación |
| :--- | :--- | :--- |
| **Recall (Sensibilidad)** | **73%** | Detectamos a casi 3 de cada 4 clientes en riesgo. |
| **Precisión** | 47% | Preferimos tener falsos positivos antes que perder clientes reales. |

### 🧠 Interpretabilidad (SHAP)
Utilicé **SHAP Values** para entender las causas de la fuga. Se descubrió que factores como la **Edad** y el nivel de **Actividad** (Active Member) son los determinantes más fuertes para la retención.

---
*Autor: Luis Mauricio Aguirre Stornaiuolo* *[LinkedIn](https://www.linkedin.com/in/mauriciostornaiuolope)*
