# Correlacion-vs-Causalidad
Proyecto en Python que ilustra la diferencia entre correlación y causalidad mediante un dataset sintético. Se analiza la relación entre ventas de helados, ahogamientos y temperatura, demostrando cómo una variable oculta puede generar correlaciones espurias usando correlación parcial y visualizaciones.
## 📌 Objetivo del proyecto

El objetivo de este proyecto es demostrar, de forma práctica y visual, la diferencia entre **correlación y causalidad** en el análisis de datos. Se pretende concienciar sobre los riesgos de interpretar relaciones estadísticas sin considerar la influencia de posibles **variables ocultas**.

---

## 📂 Descripción del dataset

Se genera un **dataset sintético** con 10.000 observaciones que incluye las siguientes variables:

- **Temperatura**: variable continua simulada dentro de un rango realista.
- **Ventas de helados**: variable dependiente de la temperatura con ruido aleatorio.
- **Ahogamientos**: variable dependiente de la temperatura con ruido aleatorio.

El dataset está diseñado para mostrar una **alta correlación entre ventas de helados y ahogamientos**, sin que exista una relación causal directa entre ambas.

---

## 🔍 Metodología

El análisis se desarrolla en varias etapas:

1. Generación del dataset mediante simulación aleatoria.  
2. Cálculo de **correlaciones directas** entre las variables.  
3. Visualización de los datos mediante:
   - Diagramas de dispersión coloreados por temperatura.
   - Mapas de calor de correlaciones.
4. Cálculo de **correlaciones parciales** para controlar el efecto de la temperatura y evaluar relaciones reales.

---

## 📈 Resultados y conclusiones

- Existe una **alta correlación directa** entre ventas de helados y ahogamientos.
- Al controlar la variable temperatura, dicha correlación **desaparece casi por completo**, evidenciando una **correlación espuria**.
- La temperatura presenta una relación fuerte con ambas variables, actuando como **factor causal**.

Este proyecto refuerza la importancia de un enfoque crítico en el análisis de datos y del uso de técnicas estadísticas adecuadas.

---

## 🛠️ Herramientas utilizadas

- Python  
- NumPy  
- pandas  
- matplotlib  
- seaborn  
