# Análisis exploratorio de condiciones operativas de maquinaria industrial

**Práctica 1 — Herramientas para Inteligencia Artificial**

**Universidad:** Universidad Técnica Particular de Loja (UTPL)  
**Programa:** Maestría en Inteligencia Artificial Aplicada  
**Autor:** Hamilton Mauricio Valer Campos

## Descripción del proyecto

Este proyecto desarrolla un análisis exploratorio de condiciones operativas de maquinaria industrial mediante Python, utilizando datos sintéticos de sensores de temperatura, vibración, velocidad de rotación y horas de operación.

El propósito es transformar los registros en información útil para apoyar la identificación preliminar de condiciones que podrían requerir inspección de mantenimiento.

## Tecnologías utilizadas

- Python
- Pandas y NumPy
- Matplotlib
- JupyterLab (entorno local)
- Google Colab (entorno en la nube)
- Git y GitHub

## Dataset

El conjunto de datos contiene **180 registros y 7 columnas originales**, correspondientes a variables operacionales de tres equipos industriales simulados.

Se incorporaron cuatro columnas adicionales:

1. `temperatura_critica`
2. `nivel_vibracion`
3. `indice_condicion`
4. `prioridad_inspeccion`

## Resultados principales

El análisis permitió identificar:

- 23 registros con temperatura igual o superior al umbral didáctico de 75 °C.
- 79 registros de vibración baja, 86 de vibración media y 15 de vibración alta.
- 33 registros clasificados con prioridad alta de inspección según las reglas definidas.

Se generaron dos visualizaciones: evolución temporal de la temperatura y distribución de niveles de vibración.

## Ejecución del proyecto

Para reproducir el análisis:

1. Descargar el repositorio.
2. Instalar las bibliotecas necesarias: `pandas`, `numpy`, `matplotlib` y `jupyterlab`.
3. Abrir `Practica_1_Mantenimiento_Predictivo_UTPL.ipynb`.
4. Mantener el archivo `datos_sensores_industriales.csv` en la misma carpeta.
5. Ejecutar las celdas en orden.

El notebook puede ejecutarse en JupyterLab o Google Colab.

## Alcance y limitaciones

Los datos son sintéticos y los umbrales utilizados tienen fines académicos. El proyecto no constituye un sistema de mantenimiento predictivo validado ni permite afirmar que se han predicho fallas reales.

## Conclusión

La práctica demuestra cómo herramientas de análisis y visualización pueden transformar datos operacionales en indicadores interpretables, estableciendo una base para futuros desarrollos de inteligencia artificial aplicada al mantenimiento industrial.
