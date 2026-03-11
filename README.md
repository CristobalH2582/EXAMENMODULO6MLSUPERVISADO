# EXAMENMODULO6MLSUPERVISADO
Entrega Examen Modulo 6
# 🛒 Predicción Inteligente de Gasto en E-commerce
> **Proyecto de Evaluación - Módulo 6: Aprendizaje de Máquina Supervisado**

Este proyecto desarrolla un modelo predictivo capaz de estimar el monto promedio de compra de un cliente en una plataforma de e-commerce. Utilizando técnicas de **Machine Learning Supervisado**, el objetivo es proporcionar al departamento de Analítica Comercial una herramienta robusta para personalizar estrategias de marketing y optimizar la captación de clientes de alto valor.

## 🚀 Estructura del Proyecto

* `analisis_gasto_clientes.ipynb`: Notebook principal con el ciclo de vida completo del modelo (EDA, Preprocesamiento, Entrenamiento y Evaluación).
* `datos/`: Carpeta (opcional) que contiene el dataset utilizado.
* `reporte_tecnico.pdf`: Documento detallado con las conclusiones de negocio y métricas finales.

## 🛠️ Tecnologías Utilizadas

* **Python 3.x**
* **Pandas & NumPy:** Manipulación y limpieza de datos.
* **Scikit-Learn:** Implementación de algoritmos de ML, preprocesamiento y validación.
* **Matplotlib & Seaborn:** Visualización de métricas y análisis exploratorio.

## 📋 Pipeline de Machine Learning

El proyecto se divide en 8 etapas clave:
1. **Fundamentos:** Definición del problema como una **Regresión**.
2. **Preprocesamiento:** Tratamiento de outliers, imputación y codificación de variables categóricas (*One-Hot Encoding*).
3. **Escalamiento:** Estandarización de variables numéricas para mejorar la convergencia de los modelos.
4. **Modelado:** Implementación de Regresión Lineal, Polinomial y Ridge.
5. **Validación:** Uso de **K-Fold Cross-Validation** para asegurar la robustez del modelo.
6. **Comparación:** Contraste de modelos regresivos frente a algoritmos de clasificación (KNN).
7. **Optimización:** Ajuste de hiperparámetros mediante **GridSearchCV**.
8. **Boosting:** Implementación de *Gradient Boosting Regressor* para capturar relaciones complejas.

## 📊 Resultados Finales

Tras la comparación de modelos, el modelo de **Regresión Ridge Optimizada** fue seleccionado por su equilibrio entre precisión e interpretabilidad:

| Métrica | Resultado |
| :--- | :--- |
| **R² (Coeficiente de Determinación)** | **0.9055** |
| **MAE (Error Absoluto Medio)** | **16.49** |
| **RMSE (Raíz del Error Cuadrático Medio)** | **20.45** |

El modelo explica el **90.5%** de la variabilidad en el gasto de los clientes, superando al modelo de Gradient Boosting en este dataset específico debido a la naturaleza lineal de las variables.

Autor. Cristóbal Hernández
