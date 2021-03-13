# Primer-proyecto
Este es un proyecto de realidad virtual, el cual es la representación en modelado a escala de un apartamento tipo loft para personas en estrato 6, donde el usuario pueda hacer un recorrido virtual del apartamento y la experiencia sea la más real posible. 

## Problemas y soluciones
El primer problema que tuvimos fue que al utilizar maya para modelar el apartamento, las texturas no se cargaban en A-frame, esto lo solucionamos llevando los modelos exportados de maya a Substance Painter donde aplicamos las texturas y posteriormente exportamos en .gltf para lograr cargar correctamente las texturas en A-frame
Otro problema se generó a partir de utilizar los modelados exportados de Substance Painter, ya que la iluminación ambiente no funcionaba de manera efectiva en ellos, lo solucionamos colocando point light en lugares estratégicos del apartamento.
Otro problema que tuvimos fue que los objetos no detectaban los mesh de los objetos para detectar la colisión con la cámara, se solucionó creando objetos primitivos de A-frame con el fin de imitar la estructura de los objetos exportados y luego se colocaron invisibles.

## Conclusión
Podemos concluir el framework web A-frame tiene un gran alcance y potencial, ya que nos permite crear variedad de entornos virtuales con muy buena calidad y con pocos recursos de hardware.
Por otra parte A-frame cuenta con muchas librerías las cuales nos permite expandir las funcionalidades según sea nuestro objetivo, también cuenta con soporte de muchos tipos de archivos, lo que hace que sea muy versátil y eficiente. 
