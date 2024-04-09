# Análisis de Datos: Resumen de Resultados y Descubrimientos

## Resumen

Este proyecto se centra en el análisis de datos recopilados de BigQuery, enfocándose en la información detallada sobre la pandemia de COVID-19, específicamente en Estados Unidos. Se llevarán a cabo técnicas de limpieza, análisis, modelado y visualización de datos para extraer insights significativos.

## Metodología

El análisis se llevó a cabo siguiendo estos pasos:

### 1. Análisis Exploratorio de Datos (EDA)

Se ejecutan consultas SQL para recuperar datos específicos de interés, como nombres de estados, fechas de pronóstico, nuevos casos confirmados, etc. Los resultados de las consultas se almacenan en DataFrames de Pandas para su posterior manipulación y análisis.

Se filtran los datos para incluir solo los estados seleccionados (Mississippi, Michigan, Oklahoma, Wisconsin y New York) y se imprimen para su revisión. Además, se realiza una segunda consulta optimizada para mejorar la eficiencia de la recuperación de datos.

El código puede servir como punto de partida para análisis más profundos de los datos de COVID-19 almacenados en BigQuery, así como para la implementación de visualizaciones más avanzadas y técnicas de análisis de datos.


### 2. Visualización  de Datos

- Se crearon visualizaciones detalladas, incluyendo gráficos de líneas, barras, gráfico circulary, dispecion y un mapa interactivos para ilustrar los resultados del análisis.
- Estas visualizaciones facilitan la interpretación de los datos y resaltan los hallazgos clave.


### Resultados.


Durante un período limitado comprendido entre el 23 de noviembre de 2020 y el 3 de diciembre de 2020, se analizó el curso de la pandemia. Se examinó la evolución de los casos confirmados y la cantidad de muertes. Además, se incluyó un mapa interactivo que destacaba las áreas con mayor incidencia de contagio.


