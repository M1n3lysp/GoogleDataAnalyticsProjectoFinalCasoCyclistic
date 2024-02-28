# GoogleDataAnalyticsProjectoFinalCasoCyclistic🚲
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




### Etapa 1 *Preguntar* 

**Antecedentes de la compañía**
Cyclistic es una compañía de préstamo de bicicletas o bicicletas compartidas fundada en 2016, que actualmente cuenta con una flota de 5,824 bicicletas georreferenciadas y bloqueadas en una red de 692 estaciones en Chicago. La compañía opera bajo un modelo de subscripción, ofreciendo pases de viaje individual, día completo así como membresías anuales.

A los clientes que compran pases de viaje individual o de día completo se denominan ciclistas ocasionales, mientras que aquellos que compran membresías anuales son miembros de Cyclistic.

#### Contexto de datos
Los datos con los que se realizó el estidio

#### Objetivo General
Diseñar estrategias de marketing dirigidas a convertir a los ciclistas ocasionales en miembros anuales.


####

Tres preguntas guiarán el futuro programa de marketing:
1.	¿En qué se diferencian los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic?
2.	¿Por qué los ciclistas ocasionales comprarían membresías anuales de Cyclistic?
3.	¿Cómo puede usar Cyclistic los medios digitales para influenciar a los ciclistas ocasionales a convertirse en miembros?

#### Interesados

●	**Lily Moreno**: Directora de marketing, responsable del desarrollo de campañas e iniciativas para promover el programa de bicicletas compartidas.

●	**Equipo de análisis computacional de datos de marketing de Cyclistic**: Equipo de analistas de datos que se encargan de recopilar, analizar e informar datos que ayudan a conducir la estrategia de marketing de Cyclistic.

●	**Equipo ejecutivo de Cyclistic**: Es quien decidirá si aprueba el programa de marketing recomendado.

#### 
**Pregunta de Negocio**: “¿Cómo utilizan las bicicletas Cyclistic los miembros anuales y los ciclistas ocasionales de manera diferente?”
1.	¿En qué se diferencian los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic?
2.
**Mi Rol**
En este escenario, soy un analista de datos junior en Cyclistic y mi equipo tiene la tarea general (ver más abajo) de diseñar estrategias de marketing

##### Tarea Empresarial
¿Qué patrones distintivos podemos identificar en el uso de las bicicletas de Cyclistic por parte de los miembros anuales y los ciclistas ocasionales?”

Identificar las métricas de comportamiento de los usuarios que distinguen a los ciclistas ocasionales de los miembros anuales y comprender en qué aspectos difieren.

Para responder a esta

Para responder a esta pregunta, analizaremos las métricas de comportamiento de ambos grupos y buscaremos patrones distintivos. A partir de ahí, formularemos hipótesis y recomendaciones estratégicas para incentivar a más ciclistas ocasionales a inscribirse en membresías anuales. ¡Sigamos pedaleando hacia las conclusiones! 🚴‍♀️🚴‍♂️

### Etapa 2 *Preparar* 
2.	Una descripción de todas las fuentes de datos utilizadas
### Etapa 3 *Procesar* 
3.	Documentación de todas las limpiezas y manipulaciones de datos
### Etapa 4 *Analizar* 
4.	Un resumen de tu análisis
### Etapa 5 *Compartir* 
5.	Visualizaciones de respaldo y hallazgos clave
### Etapa 6 *Actuar*
6.	Las tres recomendaciones más importantes basadas en tu análisis
### Etapa 7 *Preguntar* 
