# Segmentación de Clientes con RFM y KMeans

Este repositorio documenta un proyecto de análisis y segmentación de clientes con base en la metodología RFM y el algoritmo KMeans. El objetivo es identificar grupos homogéneos de clientes según su comportamiento de compra para apoyar decisiones estratégicas de negocio.

## Objetivo

Segmentar clientes utilizando la metodología RFM y agruparlos en clústeres mediante KMeans para facilitar acciones personalizadas de marketing y fidelización.

## Flujo de trabajo

### 1. Preprocesamiento de datos
- Carga de base de datos de transacciones
- Eliminación de valores nulos e inconsistencias
- Análisis de tipos de variables y distribuciones

### 2. Cálculo de métricas RFM
- Recencia: días desde la última compra
- Frecuencia: número total de compras
- Valor Monetario: monto total gastado por cliente
- Visualización de cada métrica con histogramas y boxplots
- Estadísticas descriptivas para interpretación y normalización

### 3. Segmentación con KMeans
- Aplicación del método del codo para determinar número óptimo de grupos
- Agrupamiento individual por cada métrica R, F y M
- Asignación de puntuaciones 0, 1 o 2 por métrica según clúster
- Cálculo de puntaje total para clasificar a los clientes
- Creación de segmentos: Bajo valor, Medio valor, Alto valor

### 4. Resultados y visualizaciones
- Tablas y gráficas de distribución por segmento
- Análisis de composición de cada grupo según RFM
- Visualización de clústeres en 2D si procede

## Herramientas utilizadas

- Python 3.x  
- pandas  
- numpy  
- matplotlib / seaborn  
- scikit-learn

## Conclusiones

- La metodología RFM permite identificar patrones significativos en el comportamiento de compra.
- KMeans facilita la segmentación objetiva y repetible por métrica.
- El puntaje compuesto brinda una vista clara y accionable de los perfiles de clientes.
- Este análisis puede ser integrado en campañas de marketing, CRM y estrategias de fidelización.
