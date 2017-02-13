# Algunos notebooks de Sistemas Dinámicos

Para examinar estos notebook hay que instalar
[jupyter](http://ipython.org) y luego ejecutarlo así desde este
directorio.

    jupyter notebook

Para familiarizarse con numpy recomiendo [este
tutorial](https://github.com/enthought/Numpy-Tutorial-SciPyConf-2015/blob/master/slides.pdf),
es conciso e iluminador.

También está buena [esta guía de matplotlib](http://www.scipy-lectures.org/intro/matplotlib/matplotlib.html)


## Puntos fijos

Estas funciones recurrentes a veces encuentran puntos fijos.

[Este notebook]("Puntos fijos.ipynb") muestra una ecuación que usa una función Trascendental,
por lo que no puede analizarse algebráicamente. Pero sí numéricamente,
y para analizar los números: gráficas.

[Este modelo de Glass y Pasternack]("Glass et Pasternack.ipynb") usa
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
    
