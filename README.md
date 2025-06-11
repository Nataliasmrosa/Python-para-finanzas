# Python para Finanzas: Análisis y Gestión de Carteras
Microcredencial universitaria de introducción a Python para finanzas por la Universidad Autonoma de Madrid


Este repositorio contiene el trabajo final del curso **Introducción a Python para Finanzas**, enfocado en el análisis de series temporales de precios de activos, construcción y simulación de carteras de inversión aleatorias, y proyección de su comportamiento futuro mediante simulación Montecarlo.

## Objetivo

Aplicar los conceptos vistos en clase para analizar una serie temporal de precios de activos, construir carteras de inversión y realizar simulaciones que permitan evaluar su comportamiento futuro.

## Desarrollo

1. **Selección de Activos**
Con una serie de datos historicos de varios activos se ha creado aleatoriamente grupos de 7 acctivos y se ha asegurado una correlación máxima de 0.6.

2. **Construcción de Carteras Aleatorias**
Con los activos seleccionados, se han creado 10 carteras aleatorias cuyos pesos sumen 1 y se muestran los pesos de cada cartera creada.

3. **Simulación del Comportamiento de las Carteras**
Con estas 10 carteras se han seleccionado 12 meses y se ha simulado su comportamiento con los datos historicos.
Se calcula el VaR condicional (CVaR) de cada carteras utilizando el método histórico y se ha selecciondo la cartera con menos CVaR.

4. **Simulación Montecarlo**
Por último, se ha realizado una simulación de Montecarlo para proyectar el comportamineto de la cartera seleccionada durante los próximos 3 meses.
Se han utilizado 10,000 iteraciones y se presentan resultado como la media, desviación estándar y percentiles. 
