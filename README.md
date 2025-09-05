## El lado humano detrás de los dashboards

Tecnóloga en gestión hotelera con 4 años de experiencia en atención al cliente digital, apasionada por el análisis de datos y la visualización de información.  
Me formé como Data Analyst en TripleTen Bootcamp. Actualmente estoy en busca de nuevas oportunidades laborales en este campo.

## Lenguajes y herramientas

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas)
![Seaborn](https://img.shields.io/badge/-Seaborn-4C4C4C?style=flat)
![Excel](https://img.shields.io/badge/-Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)

Competencias
Atención al detalle | Pensamiento analítico | Resolución de problemas | Organización | Adaptabilidad | Comunicación clara | Aprendizaje autónomo | Trabajo en equipo | Orientación a resultados | Gestión del tiempo

# Modelo de predicción de perdidas de clientes

Análisis de comportamiento de clientes de un gimnasio para segmentarlos en grupos y mejorar la retención a través de estrategias personalizadas.

## Objetivo
Agrupar a los clientes según su frecuencia de uso, edad, gastos y tipo de contrato para entender patrones de cancelación (churn) y fidelización.
![](assets/Histogramas.png) ![](assets/variables continuas.png) 
## Herramientas y tecnologías
- Python (Pandas, Matplotlib, Seaborn)
- Scikit-learn: KMeans
- Visualización: KDE plots, boxplots
- Análisis de clústeres y churn
![](assets/matriz de correlación.png)

## Proceso
- Limpieza de datos y escalado de variables
- Aplicación de K-Means con 5 clústeres
- Análisis de cada grupo según sus características
- Recomendaciones por segmento

![](assets/clusteres.png)

## Conclusiones
- Se identificaron grupos con alto riesgo de abandono
- Se propusieron acciones por clúster (contratos largos, promociones, fidelización)
- Visualizaciones claras del perfil de cada grupo
![](assets/distribución de caracteristicas.png) ![](assets/distribucion 2.png)   

**Puedes ver el proyecto completo [aqui](https://github.com/meli6432/Modelo-de-predicci-n-de-perdidas-de-clientes).**

# Identificación y clasificación de operadores ineficaces

Este proyecto analiza el rendimiento de operadores telefónicos en una empresa de telecomunicaciones, con el objetivo de identificar perfiles ineficaces y proponer mejoras.

## Objetivo
Detectar operadores con alto porcentaje de llamadas perdidas y largos tiempos de espera utilizando análisis exploratorio y modelos predictivos.
![](assets/pf.png) ![](assets/pf1.png)

## Tecnologías y herramientas
- Python (Pandas, Matplotlib, Seaborn)
- Scikit-learn (RandomForest, LogisticRegression)
- Tableau (para visualización final)
- Pruebas estadísticas (Mann-Whitney)

## Lo que se hizo
- Limpieza y análisis de datos históricos de llamadas
- Cálculo de KPIs: `missed_call_rate`, `avg_wait_time`, `outgoing_calls`
- Etiquetado de operadores ineficaces
- Entrenamiento de modelos predictivos
- Visualización de insights clave en Tableau

## Resultados
- Modelo Random Forest con precisión >85%
- Ranking de importancia de variables
- Recomendaciones prácticas para supervisores

![](assets/pf2.png) ![](assets/pf3.png)

**Puedes ver el proyecto completo [aqui](https://github.com/meli6432/operadores-telefonicos-ineficaces).**

# Proyecto: Análisis de Comportamiento en Reservas de Hotel
## Objetivo
Identificar patrones de comportamiento en las reservas de un hotel urbano, con énfasis en las cancelaciones, el canal de reserva, el tiempo de anticipación y el origen de los huéspedes.
![](assets/cancelacion_1.png) ![](assets/cancelacion_2.png)

## Herramientas utilizadas
- Python
- Pandas para análisis de datos
- Matplotlib y Seaborn para visualización
- Jupyter Notebook para documentación del proceso
- Dataset simulado (100 registros de reservas)

## Proceso
- Carga y exploración de datos
- Se verificó la limpieza, formatos y valores nulos.
- Se creó una variable booleana para facilitar el análisis de cancelaciones.
- Se exploraron relaciones entre variables.

## Visualización de datos
Se generaron gráficos para comprender los patrones:
- Cancelaciones por canal de reserva
- Distribución de noches por estadía
- Porcentaje de huéspedes por país

![](assets/cancelacion_3.png) ![](assets/cancelacion_4.png)

## Resultados / Conclusiones
- Booking fue el canal con menor porcentaje de cancelaciones.
- La mayoría de las estancias fueron de 5 a 7 noches.
- Perú fue el país de origen más frecuente, pero hubo diversidad internacional.
- Las habitaciones tipo Suite tendieron a tener menos cancelaciones.

**Puedes ver el proyecto completo [aqui](https://github.com/meli6432/comportamiento-reservas-hotel).**

# 📊 Proyecto de Análisis de Ventas 2024 con Power BI

## Objetivo
Diseñar un informe interactivo en Power BI Desktop que permita analizar las ventas del año 2024 desde dos perspectivas:
- Ventas por categoría de producto.
- Ventas por vendedor.

 El objetivo principal fue crear un dashboard sencillo, visual y fácil de interpretar para apoyar la toma de decisiones comerciales.

## Herramientas utilizadas
- Power BI Desktop: para la construcción de dashboards interactivos.
- Excel: base de datos con 14,834 registros de ventas.
- DAX: para la creación de medidas como Total Ventas, Total Unidades y Ticket Promedio.

## Proceso
1. Importación y limpieza de datos desde Excel.

2. Creación de medidas DAX básicas:
- Total Ventas
- Total Unidades Vendidas
- Ticket Promedio
- Número de Categorías / Vendedores

3. Diseño de visualizaciones en dos páginas:
- Página 1: Análisis por Categoría (barras, columnas, treemap y matriz).
- Página 2: Análisis por Vendedor (barras horizontales, tablas con ticket promedio y KPIs).

4. Aplicación de filtros y segmentadores por fecha, categoría y vendedor.

## Visualización de datos
1. Categorías de productos:
- Ropa, Electrónica, Comestibles, Limpieza y Bebidas.
- Se muestran ventas totales y unidades vendidas por categoría.
- Visualizaciones: gráficos de barras, columnas, treemap y matrices.
![](assets/Categoria.png)

2. Vendedores:
- Ranking de vendedores por unidades vendidas y monto total cobrado.
- Ticket promedio para evaluar eficiencia de cada vendedor.
- Visualizaciones: barras horizontales, tablas detalladas y KPIs.
![](assets/Vendedor.png)

## Resultados / Conclusiones
- Total Ventas 2024: USD $91.16 millones.
- Total Unidades vendidas: 1.07 millones.
- Mejores categorías: Ropa y Electrónica destacan en ingresos, seguidas de Limpieza y Comestibles.
- Top vendedores:
    - Tess Askew y Skyla Broomfield sobresalen con más de $9.8M cada uno en ventas.
    - Ticket promedio general: $85.49.

Hallazgo clave: las ventas están distribuidas de forma relativamente equitativa entre categorías y vendedores, lo cual refleja una red comercial sólida sin dependencia de un solo actor.

**Puedes ver el proyecto completo [aqui](https://github.com/meli6432/Ventas-Power-BI.git).**

¡Gracias por tomarte el tiempo de conocer mi trabajo!

💬 Si quieres conectar, intercambiar ideas o explorar posibles colaboraciones, estoy disponible en:

🔗 [LinkedIn – Sandra Vidal Jaramillo](https://www.linkedin.com/in/sandra-vidal-j/)
📧 meli643@gmail.com
📍 Colombia | Disponible para trabajo remoto
