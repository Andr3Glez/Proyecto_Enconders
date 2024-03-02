
Proyecto Encoders
Andre Yahir Gonzalez Cuevas

Este proyecto trata sobre poner en practica los conocimientos adquiridos hasta ahora sobre los Encoders, tanto su funcionamiento como su implementacion en distitnos proyectos.

Este proyecto se basa en la base de datos FFQH, el cual consta de datos consta de 52.000 imágenes PNG de alta calidad con una resolución de 512 × 512 y contiene una variación considerable en términos de edad, origen étnico y fondo de la imagen.

También tiene una buena cobertura de accesorios como anteojos, gafas de sol, sombreros, etc. Las imágenes fueron rastreadas desde Flickr, heredando así todos los sesgos de ese sitio web, y alineadas y recortadas automáticamente usando dlib. Sólo se recopilaron imágenes bajo licencias permisivas. Se utilizaron varios filtros automáticos para podar el conjunto, y finalmente se utilizó Amazon Mechanical Turk para eliminar alguna que otra estatua, pintura o fotografía de fotografías.

El dataset origanl tiene un peso de 2.5Tb por lo tanto se usará otra version llamada thumbnails128x128, la cual solo pesa 1.95 GB y contiene 70,000 imagenes, por lo tanto se usará este dataset, de todas formas se le haran cambios a los datos.

Uno de los cambios que se haran será cambiar la calidad por cuestiones de procesamiento y tiempos de ejecucion uno de estos es bajar la calidad de 255x255 a 64x64, de la misma forma se hará usará un porcentaje del total de datos por cuestiones de almacenamiento en este caso se usará el 15% del to tal de imagenes.

El objetivo de este proyecto es hacer un autocnoder el cual pueda, recibir imagenes las cuales tengan distintos tipo de ruidos y con ayuda del autoencoder se pueda limpiar y suavizar las imagenes y eliminar el ruido generado.
