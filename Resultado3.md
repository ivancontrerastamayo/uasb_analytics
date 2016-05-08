HALLAZGO 3
============

#Estudiantes por colegio que consumen alcohol en dias laborales o fines de semana segun el sexo#

**DataSet**: Estudiantes

El resultado mostrado en este proceso es el siguiente

edad > 19.500
|   finde > 4: GP {GP=1, MS=1}
|   finde ≤ 4: MS {GP=1, MS=2}
edad ≤ 19.500
|   edad > 17.500
|   |   laboral > 2.500
|   |   |   sexo = F: GP {GP=2, MS=2}
|   |   |   sexo = M
|   |   |   |   finde > 3.500: GP {GP=4, MS=2}
|   |   |   |   finde ≤ 3.500: MS {GP=0, MS=4}
|   |   laboral ≤ 2.500: GP {GP=69, MS=23}
|   edad ≤ 17.500: GP {GP=272, MS=12}



Imagen en el repositorio del Resultado obtenido: 
![Imagen Proceso 3](https://github.com/ivancontrerastamayo/uasb_analytics/blob/master/proceso3.png "Proceso 3")

Imagen Local del Resultado obtenido: 
![Imagen Proceso 3](/home/pc/uasb_analytics/proceso3.png "Proceso 3")

Como conclusion se puede mencionar que los estudiantes de 17 y 18 años, en su mayoria masculinos ingieren mas alcohol en dias laborales son los del colegio Gabriel Pereira.
