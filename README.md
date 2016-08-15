# Matriz de Leslie

La Matriz de Leslie se usa en ecología para modelar los cambios en una
población de organismos a través de un lapso. En este modelo la
población se divide en grupos de edad. Para cada unidad de tiempo la
población se representa con un vector con un elemento por cada clase
de edad.

Se trata de una matriz cuadrada con tantos renglones y columnas como
el vector de clases tiene elementos. En cada paso de tiempo el vector
de clases de población se multiplica por la matriz Leslie para generar
el vector del siguiente paso.

Para examinar este notebook hay que instalar
[jupyter](http://ipython.org) y luego ejecutarlo así:

    jupyter notebook
    
