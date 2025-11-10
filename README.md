# Análisis Descriptivo del Comportamiento de Ventas Globales y Desempeño Comercial

Este repositorio contiene la evidencia de aprendizaje 1 del curso, enfocada en la definición del problema y la exploración inicial de un dataset de ventas globales.

## I. Definición del Problema de Negocio

### Descripción del Problema a Abordar
El problema de negocio se centra en la necesidad de la empresa de **optimizar su estrategia comercial y de inventario** al carecer de una comprensión clara y detallada de los patrones y factores que impulsan el rendimiento de sus ventas a nivel internacional. Se busca mitigar riesgos como el exceso o falta de inventario de productos específicos y la asignación ineficiente de recursos comerciales a territorios de bajo rendimiento.

### Pregunta de Investigación Específica y Medible
¿Cómo se relacionan las variables geográficas (**COUNTRY**, **TERRITORY**), temporales (**YEAR_ID**, **QTR_ID**) y transaccionales (**DEALSIZE**) con el **ingreso total de ventas (SALES)**, y qué líneas de productos (**PRODUCTLINE**) son las que generan la mayor contribución económica para guiar decisiones de inversión y planificación estacional?

### Métricas de Éxito
Las métricas que se utilizarán para evaluar el éxito del análisis descriptivo son:
* **Total de ventas (SALES)**: Desglosado por categoría de producto y territorio.
* **Promedio de ventas por tamaño de trato (DEALSIZE)**: Para validar si los tratos "Large" son significativamente más valiosos.
* **Distribución temporal de ventas**: Análisis de las ventas por año, trimestre y mes para identificar estacionalidades.
* **Porcentaje de contribución de cada producto** al ingreso total.
* **Identificación de los tres países con mayor volumen de ventas**.
