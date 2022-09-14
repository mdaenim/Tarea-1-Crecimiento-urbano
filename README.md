# Crecimiento urbano en el Gran Área Metropolitana de los últimos 20 años

Este artículo es una recopilación del trabajo final del curso de Fotogrametría y Teledetección del segundo ciclo del 2021; elaborado por las estudiantes: 
* Daniela Amador Muñoz
* Marget Martinez

## Introducción 

El **Gran Área Metropolitana** fue creada como un instrumento para regular el crecimiento urbano, en lo que popularmente se conoce como el Valle Central. Este tiene una extensión de 196,700 ha. Pero en las últimas décadas el desarrollo urbano ha sido desordenado, o sea no sigue las políticas de ordenamiento territorial, y se ha marcado un claro patrón de expansión horizontal. En resumen, la GAM se ha expandido de forma periférica extendiendo el área de la ciudad más allá del anillo de contención. [1,2]

## Metodología

Para conocer el crecimiento urbano del Gran Área Metropolitana en los últimos 20 años, llevaron a cabo un proceso para la clasificación y extracción de la mancha urbana, el cual consistió básicamente en dos fases: 

Post-procesamiento y clasificación de las imágenes Landsat 5 y 8 en la plataforma Google Earth Engine (GEE);
Y el recorte y obtención de las áreas de las coberturas en el programa QGIS para su posterior análisis e interpretación. 

El principal insumo para el desarrollo del trabajo fueron las imágenes Landsat del programa gestionado por la NASA y el Servicio Geológico de los Estados Unidos [3]. Utilizaron los siguientes sensores: Landsat 5 para identificar la mancha urbana de la GAM para el año 2001 y el sensor Landsat 8 para el año 2021. Los dos años elegidos corresponden a un periodo de 20 años entre ambas fechas.  

## Resultados 

Los resultados mostraron como se puede ver en la *Figura 1*, que la mancha urbana para el año 2001 se limitó en su mayoría dentro del anillo de contención urbana. Lo que coincidió con los resultados de la *Tabla 1*, que indicó que la cantidad de hectáreas que representaba esta mancha de crecimiento urbano en esta fecha, eran alrededor de 43 300 ha. 


![Figura 1](https://github.com/mdaenim/Tarea-1-Crecimiento-urbano/blob/main/Figura%201.png)
Figura 1


![Tabla 1](https://github.com/mdaenim/Tarea-1-Crecimiento-urbano/blob/main/Tabla%201.jpeg)

Por otro lado, el resultado de la imagen satelital para el año 2021 como se ve en la *Figura 2* es que la mancha urbana se sale del anillo de contención, ocupando espacios donde antes había cobertura vegetal o boscosa. Esto también lo pudieron corroborar con los datos obtenidos del cálculo de áreas de la *Tabla 1* que muestra la cantidad de hectáreas correspondientes a la mancha urbana de este año, con un valor aproximado de 61 780 ha. 

![Figura 2](https://github.com/mdaenim/Tarea-1-Crecimiento-urbano/blob/main/Figura%202.jpeg)
Figura 2

Y por último, en la *Figura 3* se ve la sobreposición de las manchas urbanas del 2001 y del 2021. Acá pudieron comparar el crecimiento urbano en el periodo de 20 años, así como la cantidad de hectáreas que abarca cada uno de los años. Hay una diferencia de aproximadamente 20 400 hectáreas. La mayor parte de este crecimiento urbano se puede observar en las zonas de Cartago, Heredia y Alajuela fuera del anillo de contención urbana. Es un crecimiento que se ha dado de manera horizontal, por ello es que se observa aún más hacia las periferias del anillo de contención. Esto se deriva en distintas problemáticas que están asociadas a la manera desordenada en que se ha venido realizando este crecimiento. Esto lo podemos ver en la actualidad en factores como el transporte. Conforme aumenta la mancha urbana por fuera del anillo de contención, las distancias para el desplazamiento aumentan. Y además, se ve una disminución de la cobertura vegetal, lo que repercute en la calidad del aire y en el estado de los acuíferos.

![Figura 3](https://github.com/mdaenim/Tarea-1-Crecimiento-urbano/blob/main/Figura%203.jpeg)
Figura 3

## Referencias

1. Sánchez, L. Tendencias y patrones del crecimiento urbano en la GAM, implicaciones sociales, económicas y ambientales y desafíos desde el Ordenamiento territorial. Estado de la Nación. 2018. pp. 1-74. [Enlace a Informe Estado de la Nación](https://repositorio.conare.ac.cr/bitstream/handle/20.500.12337/2982/Tendencias_patrones_crecimiento_urbano_GAM.pdf?sequence=1&isAllowed=y) 
2. Arguedas, D. Gran Área Metropolitana: víctima y cómplice del cambio climático. Ojo al clima. julio 29, 2016. [Enlace a la página Ojo al Clima](https://ojoalclima.com/gran-area-metropolitana-victima-y-complice-del-cambio-climatico/)
3. USGS Science for a changing world. Landsat Project Description. [Enlace a la página de la USGS](https://web.archive.org/web/20160320142700/http://landsat.usgs.gov/about_project_descriptions.php)

