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

## 📂 Archivos incluidos

- `merged_df.csv`: Dataset combinado listo para visualización.
- `call_analysis.ipynb`: Notebook con todo el análisis paso a paso.
- `telecom_clients_us.csv`: Información de los clientes.
- `telecom_dataset_us.csv`: Dataset crudo de llamadas desde la empresa de telecomunicaciones.
- `README.md`: Este archivo de descripción del proyecto.
- `Dashboards telecomunicaciones`: Dashboard interactivo con un df creado a partir del análisis realizado

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

## ⚙️ Cómo usar este repositorio

1. Clona el repositorio:
   ```bash
   git clone https://github.com/HumbertoTU/ProyectoFinalSprint14.git