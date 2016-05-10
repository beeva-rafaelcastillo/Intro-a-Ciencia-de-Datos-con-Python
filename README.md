# Intro-a-Ciencia-de-Datos-con-Python
Documentación necesaria para el curso: Introducción a Ciencia de Datos con Python – Análisis y Exploración de Datos

![CursoPython](CursoPython.png?raw=true)


Requisito para asistir al curso son conocimientos de Python así como interés en avanzar en la exploración de Datos.

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [iPython Notebook](http://ipython.org/notebook.html)

El siguiente codigo os servira para instalar todas las dependencias:

```
sudo apt-get install build-essential python-dev python-setuptools \ 
						python-numpy python-scipy \ 
						libatlas-dev libatlas3gf-base \ 
						python-matplotlib python-pip python-sklearn ; sudo pip install ipython notebook pydot graphviz
``` 


Por otro lado, existen distribuciones de Python que ya incluyen todos estos paquetes, [Anaconda con Python 2.7](https://www.continuum.io/downloads) es una muy buena opcion! (Yo tengo instalada esta distribucion). Asimismo existen imagenes en [Docker](https://github.com/ContinuumIO/docker-images/tree/master/anaconda) pero he de decir que no las he usado por lo que si alguien se anima, estaria bien que nos cuente su experiencia.

**IMPORTANTE: Por favor, para comprobar el estado de la instalacion y asegurar que todos los requisitos se cumplen, por favor ejecutar el notebook Prueba_Instalacion.ipynb**. Aqui paso un [tutorial sobre notebooks](http://cs231n.github.io/ipython-tutorial/).


### ¿Cuales son los objetivos del curso?

En todo proyecto de Ciencia de Datos siempre se pueden establecer las siguientes fases:

 1. Análisis y Exploración de Datos
 2. Modelización

El objetivo de este curso introductorio es centrarse en la parte de Análisis y Exploración de Datos y aprender a manejar librerías esenciales en Python para manipular datos (Pandas y Numpy), así como librerías para representar datos (Matplotlib)


### ¿Qué temas se van a abordar en el curso?
El curso consiste en una práctica con el dataset del Titanic donde se irán analizando paso a paso las distintas variables para al final identificar que factores influyeron en la supervivencia de los pasajeros. A lo largo de la práctica los estudiantes aprenderán el manejo de datos con Pandas y a generar representaciones con matplotlib. Si hay tiempo se generara un modelo quesirva para predecir si un pasajero sobrevive o no en funcion de sus caracteristicas.

### Cuando acabe el curso, ¿qué conocimientos se habrán adquirido? 
Estudiantes sabrán manejar datasets con Pandas, representar variables e interpretar resultados.
