HALLAZGO 2
============

#Estudiantes que eligen el colegio con alguna razon, dividos segun la edad y su sexo#

**DataSet**: Estudiantes

El resultado mostrado en este proceso es el siguiente

edad > 19.500
|   internet = no: MS {GP=1, MS=2}
|   internet = yes: GP {GP=1, MS=1}
edad ≤ 19.500
|   edad > 17.500
|   |   tLLegada > 1.500
|   |   |   razon = course: GP {GP=8, MS=7}
|   |   |   razon = home: GP {GP=6, MS=6}
|   |   |   razon = other: MS {GP=1, MS=8}
|   |   |   razon = reputation: GP {GP=8, MS=2}
|   |   tLLegada ≤ 1.500
|   |   |   razon = course
|   |   |   |   final > 8.500: GP {GP=9, MS=3}
|   |   |   |   final ≤ 8.500
|   |   |   |   |   sexo = F: MS {GP=0, MS=2}
|   |   |   |   |   sexo = M: GP {GP=4, MS=1}
|   |   |   razon = home: GP {GP=20, MS=2}
|   |   |   razon = other: GP {GP=3, MS=0}
|   |   |   razon = reputation: GP {GP=16, MS=0}
|   edad ≤ 17.500: GP {GP=272, MS=12}



Imagen en el repositorio del Resultado obtenido: 
![Imagen Proceso 2](https://github.com/ivancontrerastamayo/uasb_analytics/blob/master/proceso2.png "Proceso 2")

Imagen Local del Resultado obtenido: 
![Imagen Proceso 2](/home/pc/uasb_analytics/proceso2.png "Proceso 2")

Como conclusion se puede mencionar que los estudiantes menores a 19 años, que viven a menos de dos horas del colegio lo eligen en su mayoria por estar cerca a su casa segui de los cursos que este tiene.
