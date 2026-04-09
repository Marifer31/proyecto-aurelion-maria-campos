# 📊 Proyecto Aurelion. 
### (Curso Fundamentos de Inteligencia Artificial de IBM y Guayerd)

> **Proyecto educativo de análisis de datos desarrollado con Copilot**

Bienvenido/a al repositorio de **Proyecto Aurelion**, donde se desarrolla una solución integral de análisis, modelado y visualización de datos enfocados al sector retail. El proyecto busca optimizar la toma de decisiones mediante ciencia de datos y dashboards interactivos en Power BI. Desarrollado como proyecto educativo para practicar análisis de datos con Python.

## **🚀 Tecnologías y Herramientas**

[![Python](https://img.shields.io/badge/Python->=3.8-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Scientific-013243?logo=numpy)](https://numpy.org/)
[![scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-purple.svg)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)](https://jupyter.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)](https://powerbi.microsoft.com/)
[![CSV](https://img.shields.io/badge/CSV-Databases-yellow)]()
[![Excel](https://img.shields.io/badge/Excel-Microsoft-217346?logo=microsoft-excel&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Fase%204%20Completada-brightgreen.svg)]()

## **🗂️ Estructura del Proyecto**

```
proyecto-aurelion-maria-campos
├── 📁 Base_de_datos/               # Datasets originales
├── 📁 Power_BI_Dasboard/           # Dashboard Power BI
├──  demo2_Python.ipynb           # Análisis exploratorio de datos
├──  demo3_MachineLearning.ipynb  # Modelado predictivo (ML)
├── 🐍 Programa.py                  # Programa Python para cosultar la documentacion.md
├── clientes_limpio.csv
├── productos_limpio.csv
├── ventas_limpio.csv
├── detalle_ventas_limpio.csv
├── matriz_correlacion_retail_aurelion.xlsx
├── Diagrama_de_Flujo.png
├── 📋 Documentacion.md            # Documentación del proyecto
├── 📋 Instrucciones.md            # Intrucciones para copilot
└── 📋 README.md
```

## **📊 Arquitectura de Datos**

### Fuentes
- **CSV/Excel:** La base de datos se organiza en archivos tabulares (`clientes_limpio.csv`, `productos_limpio.csv`, `ventas_limpio.csv`, `detalle_ventas_limpio.csv`), derivados tras limpieza y validación.
- **Tablas:** Clientes, Productos, Ventas, Detalle_ventas. Cada una con claves primarias y foráneas documentadas en [Documentacion.md](./Documentacion.md).

### Procesamiento (ETL)
- **Extracción y Limpieza:** Conversión y validación de tipos, fechas, claves; control de nulos y duplicados.
- **Transformación:** Corrección y estandarización de categorías, merge de tablas por claves.
- **Carga y Exportación:** Output final en archivos limpios listos para análisis (CSV).

## Análisis y Modelado

- **Análisis Exploratorio:** Se evalúan distribuciones, outliers, correlaciones y tendencias principales mediante visualizaciones.
- **Ingeniería de Variables:** Generación de nuevas variables predictoras, agregaciones y transformación de campos.
- **Modelado Predictivo:** Se implementa un algoritmo de Machine Learning con scikit-learn.
- **Evaluación:** Se emplean métricas como Accuracy para validar la calidad del modelo.
> Consulta la documentación interna en `Documentacion.md`

## 🔄 Fases del Proyecto
### **✅🔎 Sprint 1 – Introducción a la Inteligencia Artificial: comprensión de los principios básicos y casos de uso reales.**
### **✅🐍 Sprint 2 – Analizar datos con Python: programación, manipulación de datos, visualización y primeros pasos con IA generativa.**
### **✅🤖 Sprint 3 – Machine Learning: Machine Learning con Python, clasificación de datos.**
### **✅📊 Sprint 4 – Power BI: creación de dashboards, reportes interactivos y visualización de datos.**
> En el directorio `Power_BI_Dasboard/` se encuentra el dashboard interactivo desarrollado en Power BI, donde se visualizan los KPIs clave del negocio.

## 📅 Fecha

**Diciembre 2025**
