# MODELO PREDICTIVO DE LA RESPUESTA AL TRATAMIENTO DE QUIMIO-RADIOTERAPIA EN CÁNCER DE PULMÓN DE CÉLULAS NO PEQUEÑAS LOCALMENTE AVANZADO BASADO EN VARIABLES RADIÓMICAS DE CT
## Motivación del proyecto
El proyecto consiste en la extracción de características radiómicas y entrenamiento de algoritmos de aprendizaje automático para desarrollar herramientas de apoyo a la decisión médica en el CP motivado por varias razones. En primer lugar, el aumento ocurrido durante los últimos años de la prevalencia de los pacientes con CP hace que este ocupe la primera causa de muertes oncológicas en el mundo y el segundo lugar en incidencia mundial. Por ello, es necesario estimular la búsqueda y desarrollar nuevas técnicas para cambiar la forma de enfocar los tratamientos disponibles y conseguir un progreso en la obtención de resultados en estos pacientes. Esto convierte al diagnóstico precoz de la enfermedad en uno de los puntos más importantes en la práctica clínica diaria. Las imágenes radiológicas y en concreto, sus características extraíbles, son un instrumento potente no invasivo para la detección del CP y su diagnostico y futuro tratamiento. Estas, en combinación con técnicas de radiómica, suponen un nuevo enfoque de sistemas de apoyo a la detección (CADe) y sistemas de apoyo al diagnóstico (CADx) soporte, sirviendo de ayuda a los médicos en lugar de sustituirlos. De esta manera, se contribuye a mejorar en gran medida la supervivencia de estos pacientes ya que los sistemas informáticos de los que se disponen en la actualidad poseen la capacidad de percibir información que el ojo humano sería incapaz. Por consiguiente, con el análisis de estas imágenes médicas se pueden extraer nuevos datos ocultos con un valor clínico muy elevado, evaluando fácil y rápidamente la presencia o el crecimiento de un tumor durante el tratamiento. 

## Extracción de características radiómicas
La radiómica es una tecnología en auge que estudia de forma no invasiva las características que existen en las imágenes médicas y que son invisibles al ojo humano, por medio de algoritmos automáticos. La finalidad de estos procesos es asociar cada características a estados fisiológicos específicos. Sustancialmente, la radiómica extrae datos de las imágenes por medio de métodos matemáticos. 
Estas características se extraen a lo largo de una región de interés con nódulos que podrían haber pasado desapercibidos.

### Clases de características
La librería permite extraer los siguientes tipos de características:

 - First Order Statistics
 - Shape-based (2D and 3D)
 - Gray Level Co-occurrence Matrix (GLCM)
 - Gray Level Run Length Matrix (GLRLM)
 - Gray Level Size Zone Matrix (GLSZM)
 - Gray Level Dependece Matrix (GLDM)
 - Neighboring Gray Tone Difference Matrix (NGTDM)

### Filtros:
Además de las carcterísticas sobre la imagen original, también se pueden aplicar filtros y obtener imágenes derivadas:

- Laplacian of Gaussian
- Wavelet
- Square
- Square Root
- Logarithm
- Exponential
- Gradient
- Local Binary Pattern (LBP) 2D / 3D

Para más información, ver la documentación de Py-Radiomics disponible [aquí] (https://pyradiomics.readthedocs.io/en/latest/)
