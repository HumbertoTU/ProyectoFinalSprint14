# ProyectoFinalSprint14

# 📞 Telecomunicaciones CallMeMaybe Performance Analysis

Este proyecto tiene como objetivo analizar el desempeño de operadores en un centro de llamadas mediante el uso de Python, pandas y visualizaciones en Tableau. El análisis incluye eficiencia operativa, tiempos de espera, llamadas perdidas y actividad general.

## 🧠 Objetivos

- Detectar operadores ineficientes usando métricas como duración promedio de espera y tasa de llamadas perdidas.
- Identificar operadores con baja actividad (low activity).
- Visualizar tendencias de llamadas por fecha, tipo y desempeño.
- Entregar conclusiones para mejorar la eficiencia del centro de atención.

## 📊 Herramientas Utilizadas

- Python (pandas, matplotlib)
- Tableau (para dashboard interactivo)
- Jupyter Notebook
- Git/GitHub

## 📦 Entregables del Proyecto

Este proyecto incluye los siguientes materiales:

- 📓 **Notebook Jupyter (`call_analysis.ipynb`)**: Contiene el análisis completo de los datos con Python.
- 📊 **Dashboard en Tableau**: Visualizaciones interactivas para explorar tendencias y métricas clave.  
- 📽️ **Presentación en PowerPoint (`Conclusión Telecomunicaciones.pdf`)**: Expone los hallazgos, metodología y recomendaciones del análisis.

Puedes acceder a todos estos archivos en el repositorio de GitHub:  
🔗 [Repositorio GitHub - ProyectoFinalSprint14](https://github.com/HumbertoTU/ProyectoFinalSprint14)


## 📈 Dashboard en Tableau

Puedes explorar el dashboard completo aquí:  
🔗 [Ver Dashboard en Tableau](https://public.tableau.com/app/profile/humberto.torres/viz/DashboardTelecomunicacionesProyectoFinal/Dashboard?publish=yes)

## 📊 Dashboard - Descripción

Se crearon visualizaciones en Tableau para facilitar la interpretación de los datos:

### 🔹 Panel 1: Análisis General de Llamadas
- Histograma de duración de llamadas.
- Gráfico circular de participación entre llamadas internas y externas.
- Filtro interactivo por dirección de llamada.

### 🔹 Panel 2: Actividad Diaria
- Histograma de llamadas por día.
- Gráfico circular de llamadas internas vs externas.
- Filtro por tipo de llamada.

### 🔹 Panel 3: Comparativa de Métricas
- Barras horizontales que comparan la sumatoria de:
  - Duración total de llamadas
  - Número de llamadas
  - Tiempo de espera

### 🔹 Panel 4: Comparativas entre eficientes e ineficientes
  - Call Duration
  - Calls Count
  - Waiting Duration
  - Total de operadores

## 🎛️ Filtros Interactivos en el Dashboard

El dashboard cuenta con varios filtros para facilitar la exploración y el análisis detallado de los datos:

- **Is inefficient:** Permite seleccionar entre operadores *efficient* (eficientes) e *inefficient* (ineficientes).  
- **Date:** Rango de fechas para filtrar los datos, desde el **8 de agosto de 2019** hasta el **27 de noviembre de 2019**.  
- **Internal:** Filtra entre llamadas *internas* y *externas*.  
- **Direction:** Filtra por la dirección de la llamada: *in* (entrantes) o *out* (salientes).  

### 🎨 Convenciones de color

Para facilitar la interpretación visual, se utilizaron los siguientes colores en las gráficas y paneles:

- **Is inefficient:**  
  - *efficient* → color **azul**  
  - *inefficient* → color **naranja**  

- **Internal:**  
  - *llamadas internas* → color **azul**  
  - *llamadas externas* → color **naranja**
