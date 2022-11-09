# Proyecto Modular - Sistema intérprete de lenguaje de señas

El objetivo de este proyecto es desarrollar una herramienta de código abierto que mediante el uso de nuevas tecnologías como la Inteligencia artificial, permita a los usuarios utilizar un programa para agilizar la manera en la que llevan a cabo sus actividades diarias de comunicación.

## Indice



## Las librerias necesarias para la ejecucion de este proyecto de manera local son las siguientes:

|                          | Version                      | 
|--------------------------|------------------------------|
| Python                   | 3.7,                         |
| Tensorflow               | 1.5                          |
| Protobuff                | v2.19                        |
| object-detection-api     | Más actual                   |
| Numpy                    | 1.23.4                       |
| OpenCV                   | 4.6.0.66                     |
| VisualStudio C++  tools  | Más actual                   |
| MediaPipe                | 0.8.11                       |
| Anaconda                 | 2022.10                      |

## Instalacion

### Python
Para instalar python recomendamos crear un entorno de desarrollo virtual con la herramienta de anaconda, ya que nos permite manejar distintos entornos de desarrollo 
sin tener que preocuparnos por las librerias.

Pasos para instalar python:
1. Instalar Anaconda del sitio oficial. [ANACONDA](https://www.anaconda.com/)
2. Abrir el command prompt de Anaconda
3. conda create --name nombre_del_entorno_virtual --python=3.7
4. conda activate nombre_del_entorno_virtual

Listo, ya tenemos nuestro entorno de desarrollo virtual con python 3.7

### Tensorflow
Para instalar tensorflow seguiremos los mismos pasos que con Python en el Anaconda command prompt

Pasos para instalar tensorflow 1.5
1. Abrir el command prompt de Anaconda
2. conda install 1.5

En caso de que no se encuentre el repositorio podemos optar por utilizar PIP
1. pip install tensorflow==1.5

## VisualStudio C++ Tools
Es importante para poder continuar con la instalacion de este programa tener instalado esta herramienta, de lo contrario no podremos continuar con su instalacion

Pasos para instalar VisualStudio C++ Tools:
1. Descargar la herramienta del sitio oficial de Microsoft [VisualStudio C++ Toools](https://visualstudio.microsoft.com/es/vs/community/)
2. Instalar la herramienta
3. Dentro de la herramienta buscar la opcion de 'C++ Tools' y seleccionarla
4. Click en instalar

Listo, tenemos C++ Tools instalado.

## Protobuff
Para instalar Protobuff es indispensable tener las herramientas anteriores previamente instaladas.

Pasos para instalar Protobuff:
1. Ir al sitio oficial y descargar el .zip acorde a nuestra maquina (x32 o x64) [Protobuff](https://github.com/protocolbuffers/protobuf/releases)
2. Mover el archivo .zip al disco C:
3. Unzip al archivo
4. Entramos a la carpeta bin
5. Copiamos la ruta
6. En el buscador de Windows buscamos 'Edit the system enviroment variables'
7. Seleccionamos 'Path'
8. Click en 'Edit'
9. Click en 'New'
10. Pegamos la ruta de la carpeta bin previamente copiada
11. Guardamos nuestra nueva variable de entorno

Para validar que se instalo correctamente tenemos que abrir un nuevo command prompt (Es necesario que sea un command prompt nuevo si no, no se veran los cambios)
En el nuevo command prompt escribimos lo siguiente: **protoc**

Nos deberia de aparecer todas las opciones disponibles de protoc.
Listo, tenemos instalado Protobuff

## Tensorflow Object Detection API
