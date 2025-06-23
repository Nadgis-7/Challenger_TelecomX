# Challenger_TelecomX
# 📊 Análisis de Evasión de Clientes (Churn) – Telecom X

Este repositorio contiene un análisis exploratorio y visual completo del problema de **evasión de clientes (churn)** en Telecom X. Utilizando Python, Pandas y Plotly, se procesaron los datos de clientes provenientes de una API y se identificaron patrones y factores asociados con la cancelación del servicio.

---

## 📌 Objetivo del Proyecto

El propósito principal es **comprender los factores que influyen en la pérdida de clientes** para ayudar a Telecom X a mejorar su retención. Este análisis sirve como base para el desarrollo de **modelos predictivos de churn** y para tomar decisiones estratégicas basadas en datos.

---

## 🧰 Herramientas Utilizadas

- Python (v3.11+)
- Pandas
- Plotly Express
- Google Colab
- JSON API (fuente de datos)

---

## 📁 Estructura del proyecto
````plaintext 
📦 telecomx-churn-analysis
├── Challenger_TelecomX.ipynb       # Notebook principal con el análisis completo
├── TelecomX_Data.json              # Datos originales descargados desde la API
└── README.md                       # Descripción general del proyecto
````
---
## ▶️ Instrucciones para Ejecutar el Notebook

### 🔗 Opción 1: Abrir en Google Colab

1. Ir a [Google Colab](https://colab.research.google.com/)
2. Seleccionar la pestaña **"GitHub"**
3. Pegar esta URL del repositorio: [GitHub](https://github.com/Nadgis-7/Challenger_TelecomX)
4.4. Abrir el archivo `Challenger_TelecomX.ipynb`
5. Ejecutar las celdas paso a paso (`Shift + Enter`)

> 💡 También podés usar este botón directo para abrirlo en Colab:

[![Abrir en Colab](https://colab.research.google.com/drive/1JCer63zM868i707aCUdnFuq1U1BH9CGo?usp=sharing)

## 🔎 Proceso de Análisis

### 1. Importación y Limpieza de Datos
- Extracción desde API JSON
- Normalización de estructuras anidadas
- Estandarización de valores y nombres de columnas
- Creación de variables derivadas (`CuentasDiarias`)

### 2. Análisis Exploratorio (EDA)
- Distribución de Evasión por género, edad, contrato, servicios y método de pago
- Análisis de correlaciones y visualizaciones interactivas
- Cálculo de tasas de evasión por segmento

### 3. Conclusiones
- La Evasión es mayor en clientes nuevos (< 10 meses)
- Los contratos mensuales tienen alta probabilidad de evasión
- Métodos de pago como "Electronic Check" presentan más churn
- Tener servicios adicionales como TV o teléfono reduce el churn

---

## 📈 Visualizaciones Clave

- Histogramas segmentados por Evasión
- Boxplots de cargos diarios y mensuales
- Línea de tasa de evasión según tiempo de contrato
- Matriz de correlación numérica

---

## ✅ Recomendaciones

- Implementar beneficios en los primeros 6 meses
- Incentivar contratos anuales o bianuales
- Promover métodos de pago automáticos
- Combinar servicios para aumentar fidelización
- Aplicar modelos de machine learning para detección anticipada de churn

---

## 📊 Informe Final

El informe final se encuentra dentro del notebook (sección “Informe Final”) e incluye:
- Introducción al problema
- Detalles de limpieza y tratamiento de datos
- Visualizaciones con análisis interpretativo
- Conclusiones y estrategias de mejora

---

## 👩‍💻 Autor

**Nadia**  
Análisis realizado para el Challenger_TelecomX de ALURE-ORACLE, con enfoque en visualización estratégica, limpieza de datos y diseño de soluciones accionables basadas en insights.

---
