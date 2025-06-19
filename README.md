Entrega final de Data Science: Ciberseguridad - Ataques Cibernéticos

Introducción: 
En este proyecto final trabajaremos sobre los ataques cibernéticos, es decir, sobre acciones maliciosas dirigidas a sistemas informáticos, redes o dispositivos con el objetivo de robar, alterar o destruir información. Entre los más comunes se encuentran el phishing (engaño para obtener datos personales), malware (software malicioso como virus o ransomware), ataques DDoS (saturación de servidores para interrumpir servicios) y exploits (aprovechamiento de vulnerabilidades del sistema). Estos ataques pueden afectar tanto a individuos como a empresas y gobiernos, causando pérdidas económicas, robo de identidad y daño a la reputación. 

Objetivo:

Al trabajar con el dataset elegido nuestro objetivo es ver qué tipo de ataques cibernéticos son, el nivel de gravedad que tuvo, la dirección IP de origen y destino, en qué región sucedió y las acciones tomadas al respecto.


Integrantes:

-Analia Rivera

-Belén Pellejero


Datasets utilizados:

Descargado de Kaggel: https://www.kaggle.com/datasets/teamincribo/cyber-security-attacks/data ; https://www.kaggle.com/datasets/shakirul09/cyber-crimes-dataset


Estructura del repositorio:

-README

-cyber-security-attacks (dataset)

-Notebook de trabajo


Metodología:

Limpieza y exploración:

-Visualización de los faltantes

-Visualización de las columnas

-Visualización de los valores en la columna ‘Tipos de ataque’

-Visualización del contenido de las primeras y últimas filas

-Visualización del tipo de datos de las features

-Selección de las columnas con las que trabajaremos

-Visualización de las columnas seleccionadas

-Creación de un nuevo dataset con las columnas seleccionadas

-Visualización de la cantidad de columnas y filas

-Renombramos las columnas seleccionadas para mayor claridad

-Visualización de los valores en la columna ‘Nivel de gravedad’ y sus atributos únicos

-Reemplazo de los nombres de los atributos únicos de la columna Nivel de gravedad

-Graficamos las columnas Tipo de ataque, Nivel de gravedad y su relación entre ellas.

Transformación:

-Transformamos los atributos de las columnas Tipos de ataque, Acción tomada, Nivel de gravedad y Datos de geolocalización a valores numéricos

-Comenzamos normalización de la columna Datos de geolocalización  
Herramientas utilizadas: Pandas, Numpy, Seaborn, Matplotlib.pyplot, Scipy.stats, Sklearn.preprocessin (LabelEncoder, Normalizer)

Pre entrega 3 de Data Science.

Tema: Ciberseguridad

Objetivo: En esta entrega buscamos cuales fueron los paises que más ataques tubieron y de que tipo, cual fue el horario más buscado para el ataque y la industria más afectada y si el ataque fue exitoso o no.

Metodología: 
-Visualización del dataset, de la cantidad de sus columnas y filas, nombre y tipo de las columnas, faltantes.

-Al no haber faltantes realizamos una revisón más extensa.

-Eliminamos features que no nos aportaban valor al trabajo.

-Convertimos la columna datetime a dos columas separadas de fecha y hora, dejando en fecha solamente el año y en hora solo la hora.

-Creación de tabla pivot para chequear nombres de features.

-Creacion de mapa de calor para ver las cantidades por tipo y país.

-Creación de gráfico de severidad de ataque por industría.

-Contamos cuántos ataques hubo por hora y deducimos la hora más frecuente.

-Creación de tabla de exitos y fracasos de ataques cibernéticos.

-Gráficos de cantidad de ataques por país.

-Transformación de datos numéricos usando Labelencoder.

-Transformación de datos categóricos usando Onehotencoder.

-Uso de SVM para el cual lo estandarizamos usando Standard Scaler.




