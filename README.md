# Proyecto Henry Datathon

## Mercado inmobiliario
​
Dentro de la sociedad globalizada e industrializada, es sabido que los precios de los inmuebles han presentado un constante cambio, por lo que quienes deseen invertir o vender una propiedad se enfrentan al fenómeno especulativo existente en la valorización de éstos. Esto, debido a la constante tendencia de las ciudades a crecer demográfica y comercialmente, llegando a un punto en donde no se tiene certeza de la valorización real dentro del sector en donde se desee invertir. 
​
Pese a que el precio depende, en cierta medida, de las tendencias que esté teniendo el mercado inmobiliario en un determinado tiempo, poder estimar adecuadamente el valor de una propiedad es una referencia clave para entender si es una buena oportunidad, ya sea de compra o de venta.
​
## Descripción del problema
​
Usted ha sido contactado de una importante empresa inversora dentro del rubro de la inmobiliaria en Colombia, con el fin de que implemente un modelo de clasificación que permita clasificar el precio de las propiedades en venta, utilizando los datos que se han puesto a su disposición correspondientes al año 2020.
​
Para esto, específicamente, debe predecir la **categorización** de las propiedades entre baratas o caras, considerando como criterio el valor promedio de los precios (la media).


## Librerias que usamos para nuestro codigo :

-Numpy
-Pandas
-Matplotlib
-Sklearn

# Proceso :

## -Lo que primero hicimos fue elegir que columnas utilizar y cuales no , en primer medida a través de los datos nulos.

## -Luego decidimos que hacer con los datos nulos , en primera instancia tomé la decisión de cambiar los nulos por la medio o la moda dependiendo el caso.
 
 Pero creí mas conveniente hacer un modelo predictivo para llenar esos valores nulos de una manera mas eficiente.
 
 Elegimos el orden en el que llenamos esos valores nulos asi las ultimas columnas iban a tener mas datos con los cuales entrenar ese modelo , y asi ser mas efectivo.
 
## -Para lo último dejamos la columna price que tenia 70 valores nulos , le aplicamos nuestro modelo y finalmente creamos nuestra columna target para diferenciar las propiedades caras de las baratas.

## -Después de probar algunos modelos con mi dataset de entrenamiento decidi usar el árbol de decisión.

## -Entrenamos el modelo con el dataset "train" y calculamos nuestro accuracy y recall :
 
 Accuracy = 0.9586
 
 Recall = 0.8992
 
 ## Realizamos la matríz de confusión :
 
 ![image](https://user-images.githubusercontent.com/107507556/200011033-2a06ebef-5f24-41d7-8bb6-88e98fb3a329.png)
 
 ## -Y finalmente aplicamos nuestro modelo a los datos de entrenamiento obteniendo las siguientes métricas :
  
  Accuracy = 0.8559
  
  Recall = 0.6959
