---
layout: single

title: python - opencv 

excerpt: "**¿Qué es opencv?**

OpenCV es una biblioteca libre desarrollada originalmente por Intel.
Escrita originalmente en C/C++, su mejor virtud es que es multiplataforma y se 
puede ejecutar en diferentes lenguajes de programación como Java, Objective C, Python y en C#.

La visión artificial o por computadora se está utilizando cada vez más 
para el análisis y tratamiento de imágenes mediante algoritmos de inteligencia 
artificial. Uno de los usos más importantes de OpenCV en la visión por 
computadora es la detección de rostros y objetos, sobre todo en ámbitos como 
la fotografía, el marketing o la seguridad."

date: 2022-05-27

classes: wide

header:

    teaser: /assets/images/opencv/opencv.jpeg

    teaser_home_page: true
    
    icon: /assets/images/logofairy.png

categories:

    - python3

tags:  

- opencv
---

![](/assets/images/opencv/imagen1.png)

excerpt: "**¿Qué es opencv?**

OpenCV es una biblioteca libre desarrollada originalmente por Intel.
Escrita originalmente en C/C++, su mejor virtud es que es multiplataforma y se 
puede ejecutar en diferentes lenguajes de programación como Java, Objective C, Python y en C#

La visión artificial o por computadora se está utilizando cada vez más 
para el análisis y tratamiento de imágenes mediante algoritmos de inteligencia 
artificial. Uno de los usos más importantes de OpenCV en la visión por 
computadora es la detección de rostros y objetos, sobre todo en ámbitos como 
la fotografía, el marketing o la seguridad.


## Python3

```python

#!/bin/python3.9

import cv2

#"PATH DE LA IMAGEN", (0 = a gris). Por defecto 1,  muestra a color)
imagen = cv2.imread('wallpapers.png',0)

#nombre de la visualizacion
cv2.imshow('Prueba de imagen', imagen)

#Guardar IMAGEN
cv2.imwrite("test.png",imagen)

#tiempo de visualizacion(milisegundos)
cv2.waitKey(1000)

#cerrar las ventanas abiertas durante el proceso
cv2.destroyAllWindows()


```
- [Repositorio](https://github.com/emablanco/opencv)
