# Python para Finanzas: Análisis y Gestión de Carteras
Microcredencial universitaria de introducción a Python para Finanzas, impartida por la Universidad Autónoma de Madrid.

Este repositorio contiene el trabajo final del curso **Introducción a Python para Finanzas**, centrado en el análisis de series temporales de precios de activos, construcción de carteras aleatorias y simulación de su comportamiento futuro mediante métodos estadísticos y Monte Carlo.

## Objetivo

Aplicar los conceptos aprendidos en clase para:
- Analizar series temporales de precios financieros.
- Construir carteras de inversión aleatorias.
- Evaluar el riesgo mediante CVaR.
- Simular el comportamiento futuro de las carteras con Monte Carlo.

## Metodología y Desarrollo

### 1. Selección de Activos

A partir de una base de datos histórica de precios, se generaron aleatoriamente grupos de 7 activos. Se garantizó que la correlación entre ellos no superara un umbral de 0.6 para asegurar diversificación.

### 2. Construcción de Carteras Aleatorias

Con los activos seleccionados se construyeron 10 carteras aleatorias, asegurando que los pesos asignados a cada activo sumaran 1. Se presentan los pesos de cada cartera como parte del análisis.

### 3. Evaluación del Riesgo: CVaR

Se simuló el comportamiento de cada cartera durante un horizonte de 12 meses utilizando datos históricos.  
Para cada una se calculó el **CVaR (Conditional Value at Risk)** mediante el método histórico.  
Se seleccionó la cartera con el menor CVaR, como representación de la opción más robusta ante eventos extremos.

### 4. Simulación Monte Carlo

Sobre la cartera seleccionada, se aplicó una simulación de Monte Carlo con 10,000 iteraciones para proyectar su comportamiento durante los próximos 3 meses.  
Se presentan estadísticas descriptivas de la distribución simulada: media, desviación estándar y percentiles (5%, 50%, 95%).
