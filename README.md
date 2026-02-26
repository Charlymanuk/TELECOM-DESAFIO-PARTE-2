📘 README
📊 Análisis Predictivo de Cancelación de Clientes (Churn Prediction)
📌 Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos de Machine Learning capaces de predecir la cancelación de clientes (churn) a partir de variables contractuales, económicas y de servicios contratados.

A través del análisis exploratorio de datos (EDA), preprocesamiento, modelado y evaluación, se identificaron los principales factores que influyen en la cancelación y se propusieron estrategias de retención basadas en evidencia.

 **Objetivos**

Analizar patrones asociados a la cancelación de clientes.

Implementar modelos de clasificación.

Evaluar el rendimiento mediante métricas estándar.

Identificar variables más influyentes.

Proponer estrategias de retención basadas en los resultados.

**Modelos Implementados**

Se desarrollaron y evaluaron los siguientes modelos:

**Regresión Logística**

**Random Forest**

Ambos modelos fueron evaluados utilizando:

Accuracy

Precision

Recall

F1-score

Matriz de confusión

Validación cruzada (Cross-Validation)

**Principales Variables Analizadas**

Entre las variables más relevantes se encuentran:

Meses de contrato (antigüedad del cliente)

Tipo de contrato (mensual, anual, dos años)

Total gastado

Total de servicios contratados

Servicio de internet (Fibra óptica)

**Hallazgos Principales**

El análisis reveló que:

Los clientes con menor antigüedad presentan mayor probabilidad de cancelación.

Los contratos de largo plazo reducen significativamente el churn.

El gasto acumulado alto se asocia con mayor probabilidad de abandono.

El segmento de fibra óptica presenta mayor riesgo relativo.

La coincidencia de estas variables en modelos lineales y no lineales refuerza la robustez de los resultados.

**Metodología**

Limpieza y preprocesamiento de datos.

Codificación de variables categóricas (One-Hot Encoding).

División del dataset en entrenamiento y prueba.

Entrenamiento de modelos.

Evaluación mediante métricas de clasificación.

Análisis de importancia de variables.

Propuestas estratégicas basadas en resultados.

**Tecnologías Utilizadas**

Python

Pandas

NumPy

Matplotlib

Scikit-learn

**Propuestas de Mejora**

Como posibles extensiones del proyecto:

Optimización de hiperparámetros (GridSearchCV)

Implementación de modelos avanzados (XGBoost, LightGBM)

Manejo de desbalance de clases (SMOTE)

Análisis SHAP para interpretabilidad avanzada

Ajuste del umbral de clasificación

**Impacto Estratégico**

Este proyecto no solo permite predecir la cancelación de clientes, sino también:

Diseñar políticas de retención focalizadas.

Identificar segmentos de riesgo.

Optimizar estrategias contractuales.

Mejorar la toma de decisiones basada en datos.

**Conclusión**

La combinación de modelos lineales y no lineales permitió obtener una visión integral del fenómeno de cancelación. Los resultados muestran que la antigüedad del cliente y el tipo de contrato son factores protectores clave, mientras que el gasto acumulado y ciertos segmentos de servicio aumentan la probabilidad de abandono.

El análisis demuestra cómo el uso de técnicas de Machine Learning puede transformar datos en decisiones estratégicas de negocio.
