Proyecto 6 - Análisis de una empresa de telecomunicaciones
Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel para identificar patrones de uso de llamadas y mensajes, detectar valores atípicos y segmentar a los usuarios según su comportamiento y edad, con el fin de obtener información útil para la toma de decisiones.

Datasets utilizados

Se utilizaron tres conjuntos de datos:

plans.csv: Información de los planes disponibles.
users_latam.csv: Información de los usuarios (edad, ciudad, plan, fechas de registro y cancelación).
usage.csv: Registros de llamadas y mensajes realizados por los usuarios.
Etapas del análisis

Durante el proyecto se realizaron las siguientes etapas:

Carga y exploración de los datos.
Identificación de problemas de calidad.
Limpieza de datos (valores nulos, sentinels y fechas inválidas).
Cálculo de estadísticas descriptivas.
Visualización de distribuciones y detección de outliers.
Segmentación de clientes por edad y nivel de uso.
Elaboración de conclusiones y recomendaciones para el negocio.
Cómo ejecutar el notebook

El proyecto puede ejecutarse de las siguientes maneras:

Descargar el archivo .ipynb y abrirlo en Jupyter Notebook.
Abrir el notebook en Google Colab y ejecutar las celdas en orden.
Guía de reproducción
Descargar el notebook del repositorio.
Tener instaladas las librerías:
pandas
numpy
matplotlib
seaborn
Colocar los archivos plans.csv, users_latam.csv y usage.csv en la carpeta /datasets/.
Ejecutar el notebook desde la primera hasta la última celda para reproducir el análisis completo.
