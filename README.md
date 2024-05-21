# TF-Planning
Trabajo final de la materia "Introducción a las técnicas inteligentes de resolución de problemas de planificación, secuenciación y ejecución."
Alumna: Escalante, Guadalupe Sol 


El objetivo principal de este trabajo es realizar una serie de análisis sobre imágenes satelitales utilizando Python y las librerías correspondientes.
En este trabajo se generó una imagen NDVI de una fecha elegida (febrero 2023) utilizando imágenes monobanda de Landsat8 en la zona del embalse Los Molinos (ver imagen adjunta).
El proyecto python se puede consultar desde Google Colab mediante el siguiente enlace: 
https://colab.research.google.com/drive/1pFqmwCeUfd6fn8FWyxp791H2DAZZm8pI?usp=sharing

____________________________________________________________________________________________________________________________________

Contenido del Proyecto
El proyecto aborda los siguientes aspectos:

- Descompresión de Archivos ZIP.
- Análisis Exploratorio de Datos y Metadatos de la Imagen.
- Identificación y Enmascaramiento de Posibles Outliers.
- Cálculo de Máscaras.
- Recorte de Bandas.
- Cálculo de Índices Específicos (NDVI y MNDWI).


Instalación
El proyecto hace uso de las siguientes librerías de Python:
- numpy
- matplotlib
- rasterio

Es posible instalar estas librerías utilizando pip:
pip install numpy matplotlib rasterio


Instrucciones de Uso
- Clonar el repositorio.
- Asegurarse de tener instaladas las librerías necesarias.
- Ejecutar el código proporcionado en el entorno adecuado (por ejemplo, Google Colab).


Consideraciones técnicas: 
La importación de imágenes se realiza desde google drive. Para este caso particular, las imagenes tienen acceso libre. 
Se debe montar el directorio de Google Drive donde se encuentran los archivos a utilizar.
Recomiendo leer los comentarios del notebook en cada paso para comprender mejor el proceso. 




