# 📊 Proyecto de Análisis de Datos en 5 Fases

Este repositorio contiene un proyecto completo de análisis de datos dividido en 5 fases correlativas y estructuradas, con el objetivo de aplicar buenas prácticas en ciencia de datos, desde la exploración hasta la preparación final para reportes ejecutivos.

---

## 🎯 Objetivo General

Implementar un flujo de trabajo robusto para análisis predictivo supervisado, orientado a la predicción de abandono laboral (Attrition) a partir de datos de Recursos Humanos. Se contemplan todas las etapas necesarias para asegurar integridad, trazabilidad y valor analítico.

---

## 🧱 Fases del Proyecto

### 🔹 Fase 1 – Exploración de Datos (EDA)
- Revisión inicial del dataset.
- Análisis de calidad, nulos, duplicados, tipos y patrones básicos.
- Visualizaciones preliminares.

📁 [`fase1_exploracion_eda/Fase1_EDA.ipynb`](./fase1_exploracion_eda/Fase1_EDA.ipynb)

---

### 🔹 Fase 2 – ETL y Transformación
- Limpieza de columnas irrelevantes.
- Normalización de texto.
- Conversión de tipos y tratamiento de nulos.
- Exportación del dataset limpio.

📁 [`fase2_etl_transformacion/Fase2_ETL_Limpieza.ipynb`](./fase2_etl_transformacion/Fase2_ETL_Limpieza.ipynb)

---

### 🔹 Fase 3 – Análisis de Negocio
- Segmentación por rol, género, departamento.
- KPIs como tasa de abandono, antigüedad, ingresos.
- Insights para toma de decisiones.

📁 [`fase3_analisis_negocio/Fase3_Analisis_Negocio.ipynb`](./fase3_analisis_negocio/Fase3_Analisis_Negocio.ipynb)

---

### 🔹 Fase 4 – Modelado Predictivo
- Codificación de variables.
- División entrenamiento/prueba.
- Comparación de modelos (Logistic Regression y Random Forest).
- Exportación del modelo ganador.

📁 [`fase4_modelado_predictivo/Fase4_Modelo_Predictivo.ipynb`](./fase4_modelado_predictivo/Fase4_Modelo_Predictivo.ipynb)

---

### 🔹 Fase 5 – Preparación para Reportes y Power BI
- Generación de dataset final reducido.
- Cálculo de KPIs y tablas dinámicas.
- Validación de integridad para reporting.

📁 [`fase5_reporte_powerbi/Fase5_Reporte_BI.ipynb`](./fase5_reporte_powerbi/Fase5_Reporte_BI.ipynb)

---

## 📂 Dataset

El dataset base utilizado se encuentra en la carpeta [`data/`](./data/). Incluye:
- Dataset original (`HR_Analytics_original.csv`)
- Dataset limpio (`HR_Analytics_limpio.csv`)
- Dataset final para Power BI (`HR_Analytics_para_PowerBI.csv`)
- Modelo entrenado (`modelo_randomforest.pkl`)

---

## 🖼 Visualizaciones

Capturas y visualizaciones clave generadas en el análisis se encuentran en la carpeta [`img/`](./img/).

---

## ✅ Resultado Final

El modelo predictivo final permite anticipar con precisión el riesgo de abandono laboral, y los KPIs generados están listos para ser incorporados a un dashboard ejecutivo en Power BI o similares.

---

## 🔒 Licencia y Uso

Este proyecto es de uso educativo. Puede ser replicado para fines académicos o profesionales con la debida atribución.

---
