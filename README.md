# Perdidos_el_espacio
Nombre usuario:martinagg7

Link repo:https://github.com/martinagg7/fase1.git


## Archivos
   <em>Regresion lineal</em>
   
   <em>Biblioteca faker</em>
   
   <em>Enunciado</em>
  


  
## Explicación dataset
 <em>Regresión lineal</em>
 
 Para generar estos mil datos nos resulta imposible llevar a acabo mil experimentos reales. Por ello vamos iventar estos haciendo interpolaciones sucesvivas , es decir,  para calcular el tiempo correspondiente a la longitud 1.5 metros vamos hacer la media entre los tiempos asociados a los experimentos que nos da el enunciado y en función de este  completaremos el resto de los datos.

𝘊𝘰𝘮𝘰 𝘳𝘦𝘴𝘰𝘭𝘷𝘦𝘮𝘰𝘴 𝘦𝘭 𝘱𝘳𝘰𝘣𝘭𝘦𝘮𝘢.....

Es el eje 0X de nuestra gráfica vamos a representar el dato 1/(t^2) y el 0Y repesentaremos 2L.Por lo tanto sobre esta nube de mil puntos , calcularemos la recta de regresión cuya pendiente será la gravedad del planeta en el que estamos y el coeficiente de correlación el error cometido en el cálculo de esta .

        

    
 <em>gráficos</em>
 
      -Regresión lineal
      -Graficas t^2 frente a 2l y L frente a t^2
      -Variación gravedad
      
 
      
 <em>Biblioteca faker</em>
 
 Vamos a inventarnos mediante la biblioteca faker mil datos para introducir en nuestro dataset.Este contendrá las siguientes columnas

•	L:longitud

•	T:tiempo de caida

•	G:gravedad

Esta será la formula 2L/(T^2) que emplearemos para calcular cada valor de la gravedad.Además añadiremos tambien ,tres columnas que nos indicaran los tres planetas más probabables en los que nos podemos encontrar en función de la gravedad de cada dato.Y por último una columna con el error que hemos cometido en cada medición de la gravedad

 <em>gráficos</em>
 
      -Posibilidad de cada planeta
      -Histograma de todas la variables
      -Mapa de confusión para el cálculo del planeta más proabable
 
