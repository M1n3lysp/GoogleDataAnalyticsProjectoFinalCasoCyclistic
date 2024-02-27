# GoogleDataAnalyticsProjectoFinalCasoCyclistic
Como parte del proyecto final del 8vo curso del **Certificado profesional de Análisis de Datos de Google**
***Curso final de análisis computacional de datos de Google: completa un caso práctico*** 

Caso práctico del análisis de bicicletas compartidas Cyclistic aplicando los pasos del proceso de análisis de datos: **Preguntar**, **Preparar**, **Procesar**, **Analizar**, **Compartir** y **Actuar**. 
Utilizando Excel y RStudio para limpieza de datos y reproducción de los pasos de limpieza y análisis.

# Identificando el comportamiento de usuarios ocasionales y socios anuales de bicicletas compartidas Cyclistic.

#### *Un análisis para comprender las diferencias entre los patrones de uso para incrementar la plantilla de miembros anuales*.

### Introducción
En este estudio, exploraremos los datos de uso del sistema de bicicletas compartidas Cyclistic durante el período de enero de 2023 a enero de 2024. Cyclistic es una empresa de alquiler de bicicletas con estaciones en diversas ubicaciones de la ciudad de Chicago. Nuestro objetivo es comprender los patrones de uso entre ciclistas ocasionales y socios anuales, a fin de identificar tendencias y proponer recomendaciones para una campaña de marketing que busca convertir usuarios ocasionales en miembros de Cyclistic.

###Metodología

Se aplicarán los pasos del proceso de análisis de datos: **Preguntar**, **Preparar**, **Procesar**, **Analizar**, **Compartir** y **Actuar**. 
Obtención de Datos: Descargamos los datos históricos de [Cyclistic](https://divvy-tripdata.s3.amazonaws.com/index.html), que incluyen información sobre viajes, estaciones, tipo de usuarios y fechas.

[Licencia](https://divvybikes.com/data-license-agreement)


[enlace en línea](http://www.limni.net)


Limpieza y Preparación de Datos: Realizamos una limpieza exhaustiva de los datos, tratando valores nulos, duplicados y errores. Además, creamos variables adicionales para facilitar el análisis.
Análisis Exploratorio de Datos (EDA):
Distribución de Viajes: Exploramos la distribución de viajes por hora, día de la semana y estación.
Perfiles de Usuarios: Identificamos diferentes tipos de usuarios (suscriptores, clientes ocasionales) y analizamos sus patrones de uso.
Duración de Viajes: Estudiamos la duración promedio de los viajes y su variación a lo largo del año.
Análisis Temporal:
Tendencias Mensuales: Visualizamos las tendencias mensuales de uso de bicicletas.
Comparación entre Años: Comparamos los datos de 2023 y 2024 para detectar cambios significativos.
Recomendaciones:
Mejora de Estaciones: Identificamos estaciones con alta demanda y proponemos mejoras en infraestructura.
Promociones Estratégicas: Sugerimos estrategias de promoción para aumentar la adopción de usuarios.
Conclusiones
En este estudio, hemos explorado los datos de Cyclistic y proporcionado recomendaciones para optimizar el sistema de compartición de bicicletas. Esperamos que esta información sea útil para la toma de decisiones y la mejora continua del servicio.




### Etapa *Preguntar* del Proceso de Análisis de Datos

Antecedentes de la compañía
Cyclistic es una compañía de préstamo de bicicletas o bicicletas compartidas fundada en 2016, que actualmente cuenta con una flota de 5,824 bicicletas georreferenciadas y bloqueadas en una red de 692 estaciones en Chicago. La compañía opera bajo un modelo de subscripción, ofreciendo pases de un sólo viaje, día completo así como membresías anuales.

### Contexto de datos
Los datos con los que se realizó el estidio


1.	¿En qué se diferencian los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic?
