En el Modelo para las variables categoricas y numericas he
optado por una sigmoide.

en el modelo CNN por una VGG16 al que se le ha aplicado
varios filtros de regularizacion al Clasificador.

En la hibrida he combinado las dos capas y utilizando
para la prediccion otra sigmoide.

Los resultados podrian ser mejores pero requeririan de mas pruebas y tiempo, aumentar los datos de entrenamiento,variables, etc.
Por ejemplo la variable de los precios parece seguir una distribucion
donde se acumulan los valores en la parte izquierda de la distribucion
y formando una cola a medida que se desplaza a la derecha. No he tenido tiempo pero
tambien podria probar a trasformar con el logaritmo de esta variable de forma que su distribucion
se asemejara mas a una distribucion gausiana.

La dinamica de las CNN mas o menos las he entendido, pero creo que es el tiempo, con
pruebas de ensayo error, combinacion de tecnicas, etc las que iran mejorando el 
proceso de aprendizaje.
