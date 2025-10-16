# IA_Taller2_Corte2

## Información Académica

* *Universidad:* Universidad del Pacífico.
* *Carrera o Programa:* Ingeniería en sistemas.
* *Asignatura:* Inteligencia Artificial (IA)
* *Integrantes del Grupo:*
   
    * ANDRES STEVEN RIVAS SALAS
    * KEVIN JOSEPH VALBUENA PÉREZ
    * RUBEN DARIO BARONA

---

##  Objetivo del trabajo
Aplicar los fundamentos de la programación en **Python** para la manipulación y análisis de datos, utilizando las librerías especializadas **NumPy** y **Pandas**.  
El taller busca fortalecer las competencias en el uso de herramientas computacionales para el procesamiento de información estadística, orientadas al campo de la **Inteligencia Artificial y la Ciencia de Datos**.

---

## Descripción del proyecto o taller
Este taller está basado en el notebook oficial del repositorio [Inteligencia_Artificial de WilmanAQ](https://github.com/wilmanAQ/Inteligencia_Artificial/blob/IA/notebook/introducci-n-a-estad-stica-para-data-science.ipynb), el cual introduce los fundamentos de **estadística aplicada a la ciencia de datos**.  
A partir de dicho material, se desarrollaron ejercicios prácticos en Google Colab aplicando conceptos estadísticos mediante el uso de librerías como **NumPy** y **Pandas**, para la creación, manipulación y análisis de conjuntos de datos.

---

##  Desarrollo o explicación de lo que se hizo

### 🔹 Metodología aplicada
1. Estudio del contenido teórico sobre estadística básica para Data Science.  
2. Implementación de los ejercicios en Google Colab.  
3. Aplicación de las librerías **NumPy** y **Pandas** para el manejo de arrays y estructuras tipo DataFrame.  
4. Análisis de resultados y representación de la información en formato tabular.  

---

### 🔹 Pasos realizados para resolver el ejercicio
- Importación de librerías esenciales (`numpy`, `pandas`, `matplotlib`).  
- Creación de vectores y matrices utilizando **NumPy**.  
- Cálculo de medidas estadísticas como la **media, mediana, moda, varianza y desviación estándar**.  
- Generación de datos simulados y posterior análisis con **Pandas**.  
- Representación gráfica de distribuciones de datos y comportamiento de variables.  

---
### 🔹 Interpretación y análisis de resultados

Los resultados obtenidos permitieron observar cómo las librerías NumPy y Pandas facilitan el tratamiento y análisis de datos, proporcionando métodos eficientes para calcular medidas de tendencia central y dispersión.
Además, se evidenció la importancia de estructurar los datos correctamente para su posterior análisis, lo cual constituye una base fundamental en proyectos de Inteligencia Artificial y Data Science.

----
### 🔹 Conclusión

El desarrollo del taller permitió reforzar los conocimientos en manipulación de datos mediante Python, aplicando los principios básicos de la estadística descriptiva con herramientas computacionales modernas.
Se demostró la capacidad de NumPy y Pandas para optimizar el trabajo con grandes volúmenes de información, facilitando la toma de decisiones basada en datos.

---

### 🔹 Código relevante o fragmentos de código

```python
import numpy as np
import pandas as pd

# Cálculo de medidas estadísticas
print("Media:", np.mean(datos))
print("Mediana:", np.median(datos))
print("Desviación estándar:", np.std(datos))
