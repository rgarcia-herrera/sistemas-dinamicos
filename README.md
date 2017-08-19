# Algunos notebooks de Sistemas Dinámicos

Este repositorio contiene varios notebooks de
[Jupyter](http://jupyter.org) con experimentos computacionales sobre
sistemas dinámicos, algunos dellos con dinámicas no-lineales. Varios
son problemas de libros.

## ¿Qués un notebook?

Es un documento que mezcla hipertexto y notación matemática con código
fuente de computadora, controles interactivos y gráficas, para
documentar y permitir la exploración de datos y modelos.

Jupyter permite la creación de notebooks en diferentes lenguajes de
programación, los notebooks de este proyecto están escritos en
[Python](http://python.org). Los archivos que terminan con *.ipynb*
son notebooks (interactive python note book). No he ligado todos los
que describo a continuación.

## Correr notebooks

GitHub permite examinar los documentos pero sin interactividad. Para
poder experimentar editando el código fuente o con los controles
interactivos es necesario abrirlos con Jupyter, no basta abrirlos en
GitHub.

Así que hay que:

1. instalar jupyter

2. descargar o clonar este repositorio

3. correr jupyter desde el directorio donde se haya descargado o clonado

Si estas instrucciones parecen demasiado pregunte dellas a algún amigo
hacker, será más rápido así.

## Puntos fijos

Estas funciones recurrentes a veces encuentran puntos fijos.

[Este notebook](PuntosFijos.ipynb) muestra una ecuación que usa una función Trascendental en 
por lo que no puede analizarse algebráicamente. Pero sí numéricamente,
y para analizar los números: gráficas.

[Este modelo de Glass y Pasternack](Glass_Pasternack.ipynb) usa
sympy para mecanizar el análisis algebráico. Además tiene widgets que
permiten la exploración interactiva del modelo.


## Sucesión de Fibonacci

La característica de esta sucesión es que cada número es la suma de
los dos que lo preceden. Por definición la sucesión empieza con 1,1, a
veces con 0,1. Tiene aplicaciones muy interesantes, muchas tienen que
ver con patrones de crecimiento en sistemas biológicos.

En [este notebook](Fibonacci.ipynb) se presenta un análisis de su
ecuación de recurrencia y de su fórmula cerrada.


## Matriz de Leslie

La Matriz de Leslie se usa en ecología para modelar los cambios en una
población de organismos a través de un lapso. En este modelo la
población se divide en grupos de edad. Para cada unidad de tiempo la
población se representa con un vector con un elemento por cada clase
de edad.

En [este
notebook](https://github.com/rgarcia-herrera/sistemas-dinamicos/blob/master/Leslie%20Model.ipynb)
se implementa y analiza el modelo.


# Referencias

Para familiarizarse con numpy recomiendo [este
tutorial](https://github.com/enthought/Numpy-Tutorial-SciPyConf-2015/blob/master/slides.pdf),
es conciso e iluminador.

Las gráficas están hechas con MatPlotLib. Está buena [esta guía de
matplotlib](http://www.scipy-lectures.org/intro/matplotlib/matplotlib.html)

Algunos notebooks usan [SymPy](http://sympy.org) para hacer cómputo
simbólico.

Los notebooks interactivos usan [widgets de ipython](https://ipywidgets.readthedocs.io/en/latest/examples/Widget%20List.html).

Hay que explorar esta biblioteca:
https://github.com/gboeing/pynamical
