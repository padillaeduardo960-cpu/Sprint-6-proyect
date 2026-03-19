Este proyecto busca detectar patrones que permitan anticipar si un videojuego tendrá éxito o no, con el fin de apoyar la planificación de futuras estrategias publicitarias. El estudio se realizó por regiones —incluyendo América del Norte, Europa, Japón y otras zonas— y abarcó distintas plataformas, como Wii, Xbox 360 y las diferentes versiones de PlayStation hasta la versión 6.

Librerias usadas en este proyecto:
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns
- import numpy as np
- from scipy import stats

Se presenta el dataset usado para el analisis:
Este conjunto de datos reúne información sobre diversos videojuegos lanzados entre 1980 y 2016. Incluye datos como el año de lanzamiento, la plataforma (por ejemplo, PS4, Xbox One o PC), las calificaciones de usuarios y críticos, así como las cifras de ventas en distintas regiones (América del Norte, Europa, Japón y otras zonas).

En términos generales, los resultados muestran que:

- Tomar en cuenta las particularidades del mercado objetivo es fundamental, ya que cada región presenta comportamientos y dinámicas distintas.

- Desarrollar un videojuego acorde a los géneros más demandados en ese mercado puede influir notablemente en su desempeño. Asimismo, la plataforma elegida juega un papel relevante.

- No obstante, al analizar las plataformas, también es importante considerar el año de lanzamiento, ya que este puede afectar cuál domina en ventas.

- Por último, no se observa una relación clara entre las calificaciones de los críticos y las ventas, por lo que este factor no resulta decisivo.
