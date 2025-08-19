📊 **Predicción de Cancelación de Clientes en Telecomunicaciones**
📖 **Descripción General**

Este proyecto tiene como propósito el análisis y la predicción de la cancelación de clientes (churn) en una empresa de telecomunicaciones. La tasa de cancelación representa un indicador crítico en este sector, ya que impacta directamente en la rentabilidad, la planificación de recursos y la sostenibilidad del negocio.

A través de un análisis exploratorio de datos (EDA) y la preparación de información estructurada, se busca comprender los factores que influyen en la decisión de los clientes de abandonar el servicio, con el fin de generar posteriormente modelos predictivos basados en técnicas de aprendizaje automático (Machine Learning).

🎯 **Objetivos del Proyecto**

Analizar el comportamiento de los clientes mediante un estudio exploratorio de las variables más relevantes.

Identificar patrones y relaciones entre los factores que influyen en la cancelación del servicio.

Construir visualizaciones estadísticas que faciliten la interpretación de los datos.

Preparar el dataset para etapas posteriores de modelado predictivo.

🧩 **Metodología**

La metodología aplicada se desarrolló en diferentes etapas:

1.- Carga y preparación del dataset

2.- Lectura de datos en formato .csv.

3.- Inspección inicial de filas, columnas y tipos de datos.

4.- Limpieza de datos para garantizar consistencia.

5.- Análisis Exploratorio de Datos (EDA)

6.- Estadísticos descriptivos para cada variable.

7.- Identificación de valores atípicos y ausentes.

8.- Estudio de correlaciones entre variables numéricas y categóricas.

9.- Visualización

10.- Gráficos de distribución para variables individuales.

11.- Diagramas de dispersión y de correlación.

12.- Comparación de variables respecto a la variable objetivo (churn).

13.- Preparación de datos para modelado

14.- Transformación de variables categóricas.

15.- Normalización y estandarización de datos relevantes.

16.- Conformación de un dataset optimizado para futuras fases de Machine Learning.

🛠️ **Herramientas y Tecnologías**

Lenguaje de programación: Python 3

Entorno de desarrollo: Jupyter Notebook / Google Colab

***Librerías principales:***

pandas → Manipulación y análisis de datos.

seaborn → Visualización estadística.

matplotlib → Gráficos y exploración de datos.

📊 **Resultados Obtenidos**

Identificación de variables críticas asociadas a la cancelación, tales como el tipo de servicio, la duración de la permanencia del cliente y características demográficas.

Obtención de gráficos explicativos que permiten comprender las relaciones entre variables y su influencia en el churn.

Generación de un dataset estructurado y optimizado para el entrenamiento de modelos predictivos.

🔮 **Futuras Líneas de Trabajo**

Este proyecto constituye la segunda parte de una investigación más amplia. Los próximos pasos incluyen:

Implementación de modelos de clasificación supervisada (árboles de decisión, random forest, XGBoost, redes neuronales).

Comparación del rendimiento de los modelos mediante métricas como:

Accuracy

Precision

Recall

F1-Score

AUC-ROC

Desarrollo de un sistema de detección temprana de clientes en riesgo de cancelación, con posibles aplicaciones en estrategias de retención y fidelización.

▶️ **Reproducción del Proyecto**

Clonar este repositorio:
``` bash
git clone https://github.com/tu_usuario/TelecomX_proyecto_parte2.git
cd TelecomX_proyecto_parte2
```

Instalar las dependencias necesarias:
```bash
pip install pandas seaborn matplotlib
```
Abrir el notebook en Jupyter o Google Colab:
jupyter notebook Proyecto_TelecomX_Parte2.ipynb
Ejecutar las celdas en orden para reproducir el análisis.
