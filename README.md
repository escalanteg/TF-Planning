# TF-Planning
Trabajo final de la materia "Introducción a las técnicas inteligentes de resolución de problemas de planificación, secuenciación y ejecución."
Alumna: Escalante, Guadalupe Sol 

En este trabajo se generó una imagen NDVI de una fecha elegida (febrero 2023) utilizando imágenes monobanda de Landsat8 en la zona del embalse Los Molinos. 

El programa realiza, a grandes razgos, los siguientes procesos: 
● descomprimir los archivos
● analisis de la imagen de calidad para detectar presencia de nubes
● realiza un análisis exploratorio de los datos y metadatos de la imagen y los muestra junto con la representacion de la misma en escala de grises
● calcula NDVI para toda la escena
● calcula MNDWI para clasificar agua/no agua
● enmascara el indice NDVI calculado para conservar solo los valores dentro del agua

Luego de estos procesos se obtiene una imagen de NDVI dentro del lago:
![image](https://github.com/escalanteg/TF-Planning/assets/169058583/321539fc-4b94-4fec-9ba4-7e94adbebca8)
