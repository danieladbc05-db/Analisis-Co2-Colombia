# Análisis-Co2-Colombia
Actividad 4 - Introducción Ciencia de Datos

# Análisis de emisiones de CO₂ en Colombia

**Actividad 4 – Introducción a la Ciencia de Datos**

## Integrantes
- Daniel Carrillo — GitHub: Dancar2002
- Daniela Baquero — GitHub: danieladbc05-db

## Objetivo
Analizar la evolución histórica de las emisiones de dióxido de carbono (CO₂) en Colombia mediante técnicas de limpieza de datos, visualización y regresión lineal.

## Fuente de datos
Our World in Data: https://ourworldindata.org/co2-emissions

Base de datos: https://github.com/owid/co2-data

## Metodología
1. Descarga y selección de los datos correspondientes a Colombia.
2. Identificación y eliminación de valores faltantes y duplicados.
3. Visualización de la evolución histórica de las emisiones.
4. Entrenamiento y evaluación de un modelo de regresión lineal.
5. Interpretación de resultados y conclusiones.

## Resultados principales
- Registros originales de Colombia: 276.
- Registros válidos después de la limpieza: 170.
- Período analizado: 1856–2025.
- MAE: 10,861 millones de toneladas.
- RMSE: 12,080 millones de toneladas.
- R²: -0,441.

El modelo permite estudiar la tendencia histórica, pero presenta limitaciones para predecir emisiones futuras.

## Notebook definitivo
[Ver análisis completo](Analisis_CO2_Colombia_FINAL.ipynb)

## Ejecución
Abrir el notebook definitivo en Google Colab y ejecutar las celdas en orden. Se requiere acceso a internet para descargar la base de datos.

## Trabajo colaborativo
El repositorio conserva los avances y el historial de commits realizados por ambos integrantes. Las versiones anteriores se mantienen como evidencia del proceso de desarrollo.

## Referencia
Ritchie, H. y Roser, M. (2020). CO₂ emissions. Our World in Data. https://ourworldindata.org/co2-emissions
