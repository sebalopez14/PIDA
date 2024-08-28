# Análisis del Sector de Telecomunicaciones en Argentina

## Introducción
Este proyecto fue desarrollado en el contexto de una empresa de telecomunicaciones en Argentina, cuyo objetivo es analizar el comportamiento del sector a nivel nacional, con un enfoque especial en la expansión del acceso a internet y la calidad del servicio. La empresa busca mejorar su oferta de servicios, identificar oportunidades de crecimiento y personalizar soluciones para sus clientes.

## Contenido del Repositorio
Este repositorio contiene todos los archivos necesarios para replicar el análisis y las visualizaciones desarrolladas durante el proyecto. A continuación se detalla la estructura del repositorio:

- **Dashboard.pbix**: Archivo del dashboard desarrollado en Power BI, que contiene todas las visualizaciones y KPIs creados.
- **EDA.ipynb**: Notebook de Jupyter que documenta el análisis exploratorio de datos (EDA) y cálculos preliminares.
- **expectativas-inflacion-a-doce-mes.csv**: Archivo CSV que contiene datos que suponen ser la inflacion real de los ultimos años (A falta de dataset con la informacion concreta).
- **Internet.xlsx**: Archivo excel con hojas de datasets a trabajar. 
- **Internet_Datos_Combinados.xlsx**: Archivo excel de salida una vez terminado el EDA, con todas las tablas unificadas en una.
- **Internet_Final.xlsx**: AArchivo excel de salida una vez terminado el EDA, contiene los datos finales procesados y listos para ser utilizados en el análisis y visualización dividido en diferentes.
- **README.md**: Este archivo, que proporciona una visión general del proyecto, su estructura, y cómo utilizar los archivos contenidos en el repositorio.


## Metodología
El proyecto se desarrolló en varias etapas, cada una con un enfoque específico para abordar los objetivos del análisis:

### 1. Exploración y Limpieza de Datos (EDA)
- **Limpieza de Datos**: Se realizó una limpieza de los datos, eliminando valores faltantes y registros duplicados, y asegurando la coherencia en las columnas de fechas y valores.
- **Análisis Descriptivo**: Exploración inicial de los datos para identificar patrones, tendencias, y posibles outliers en variables clave como el acceso a internet, tecnologías utilizadas y velocidades de conexión.

### 2. Cálculo de KPIs
Se desarrollaron varios KPIs clave para medir el desempeño y crecimiento del servicio de telecomunicaciones:

- **KPI de Acceso a Internet**: Medición del crecimiento en el acceso a internet por cada 100 hogares en cada provincia.
- **KPI de Velocidad Alta**: Evaluación del porcentaje de conexiones que superan los 30 Mbps, lo cual es un indicador de la calidad del servicio.
- **KPI de Churn Rate (Tasa de Cancelación)**: Análisis de la tasa de cancelación de servicios, crucial para mantener la base de clientes y la estabilidad financiera.
- **KPI de Ingreso Ajustado por Inflación**: Ajuste de los ingresos nominales según la inflación promedio para evaluar el poder adquisitivo real.

### 3. Desarrollo del Dashboard en Power BI
Desarrollo de Dashboard a presentar, profundizando en los KPI's y analizandolos a travez del tiempo. Logrando insights y entendimiento de la situacion de la empresa.

## Herramientas Utilizadas
- **Python**: Para el análisis exploratorio de datos y la creación de cálculos preliminares.
- **Power BI**: Para la creación del dashboard interactivo y la visualización de datos.
- **DAX (Data Analysis Expressions)**: Para la creación de medidas y cálculos avanzados en Power BI.
- **Git**: Para cargar el repositorio.

