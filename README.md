# Análisis Exploratorio de Datos (EDA) de Citi Bike - Primer Trimestre 2017

## 🎓 Contexto Académico

**Asignatura:** Sistemas de Big Data
**Programa:** Curso de Especialización en Big Data e Inteligencia Artificial

## 1. Objetivo del Proyecto

El objetivo principal es aplicar técnicas de **Análisis Exploratorio de Datos (EDA)** al *dataset* de viajes de Citi Bike (Jersey City, Q1 2017) para:

* Limpiar, transformar y agregar la información de viaje.
* Identificar patrones de uso y tendencias temporales.
* Validar la hipótesis de que el sistema opera primordialmente como un servicio de **trayecto habitual (*commuting*)**.

## 2. Metodología y Tecnología

| Componente | Descripción |
| :--- | :--- |
| **Plataforma** | Jupyter Notebook (`file.ipynb`) |
| **Librerías Clave** | **Pandas** (manipulación y agregación de datos) y **Matplotlib/Seaborn** (visualización para la inferencia de patrones). |
| **Dataset de Entrada** | `ny_citibikes_raw.xlsx` |
| **Procesos Clave** | Gestión de valores atípicos (outliers) en la duración de viajes y análisis de frecuencia temporal. |

## 3. Conclusiones Clave del EDA

1.  **Uso de *Commuting***: La **duración media de 9.58 minutos** y los picos de actividad en días laborables confirman que el sistema se utiliza mayoritariamente para la **movilidad de cercanía y laboral**.
2.  **Identificación de Nodos (Hubs)**: Las estaciones **Grove St PATH** y **Exchange Place** concentran el tráfico (Top 2), funcionando como **nodos multimodales** críticos que enlazan el servicio de bicicleta con el transporte interurbano (hacia Nueva York).
3.  **Fidelidad del Usuario**: El 98.11% de los viajes son realizados por **Usuarios Suscriptores**, lo que subraya el carácter rutinario y fidelizado del uso del servicio.
