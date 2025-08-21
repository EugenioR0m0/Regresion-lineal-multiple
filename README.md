# Regresion-lineal-multiple

# Regresión Lineal Múltiple: Dataset NASA

Este proyecto implementa un modelo de **regresión lineal múltiple** para analizar cómo diferentes variables físicas afectan la **presión**.  
El trabajo se basa en la base de datos **Base_de_Datos_NASA.csv**, que contiene mediciones experimentales de distintas variables asociadas.  

---

## Descripción del proyecto

- La base de datos incluye las siguientes columnas:
  - **frecuencia**  
  - **angulo**  
  - **longitud**  
  - **velocidad**  
  - **espesor**  
  - **presion** (variable dependiente)

- El objetivo fue construir un modelo que explique y prediga la **presión** en función de las otras variables.  
- Se siguieron los pasos metodológicos solicitados en la rúbrica de la actividad.  

---

## Metodología

1. **Exploración de datos**  
   Se importó el archivo CSV, se verificaron las dimensiones de la base de datos y se visualizaron las primeras filas.  

2. **Preparación de datos**  
   Se definió la variable dependiente (**presion**) y las variables independientes.  
   Posteriormente, se dividió la base en conjuntos de **entrenamiento (70%)** y **validación (30%)**.  

3. **Ajuste del modelo**  
   Se construyó un modelo de regresión lineal múltiple con `statsmodels.OLS`, obteniendo coeficientes, valores p y el resumen estadístico completo.  

4. **Identificación de variables significativas**  
   Se evaluaron los **p-values** para determinar cuáles variables resultaron estadísticamente relevantes en la explicación de la presión.  

5. **Evaluación del modelo**  
   Se calcularon las métricas de desempeño: **RSE** y **R²** en entrenamiento y validación.  

6. **Visualización**  
   Se elaboró una gráfica comparando los valores reales vs los valores estimados del modelo.  

---

## Resultados principales

- Se obtuvo un modelo de regresión lineal múltiple con la **presión** como variable dependiente.  
- Se identificaron las variables con mayor relevancia estadística en la explicación del fenómeno.  
- Las métricas de error y el coeficiente de determinación mostraron el grado de ajuste del modelo.  
- La gráfica final permitió visualizar la relación entre valores observados y estimados.  

---

## Tecnologías utilizadas

- Python 3  
- pandas  
- numpy  
- statsmodels  
- matplotlib  
- seaborn

- [Reporte en ipynb](Regresion_M.ipynb)
- [Reporte en html](Regresion_M.html)
- [Base de datos](Base_de_Datos_NASA.csv)
