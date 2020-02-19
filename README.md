# Practica tableau

La pregunta para comenzar la practica ha sido la de mostrar los barrios de madrid con un promedio del precio mas la tarifa de limpieza mas bajo ademas de pintar las barras para ver los que tinen mas reviews.

en la primera hoja, he filtrado por barrios y he puesto un parametro que se llama Nº barrios que muestra los 10 mas baratos, tambien he aplicado el filtro para todas las hojas y asi se me filtren las demas hojas con esos valores. he creado un campo calculado que me hace el promedio de la suma del precio mas la tarifa de limpieza que es la medida que usare para las vistas.

en la segunda hoja he creado una jerarquia con tipo de propiedad y tipo de habitacion para que me muestre los tipos por el precio total  tambien lo he filtrado por el tipo de propiedad

 en la tercera hoja he realizado un mapa para ver el nivel de precio segun el codigo postal  donde he creado un campo calculado que me indica tres niveles de precios: baratos, precio medio y caros. Facilmente podremos diferenciar cual es el nivel. tambien he asociado otra hoja a la descripcion para que me muestre el precio total por codigo postal y como habia codigos postales que no tenian ningun airbnb he creado otro campo calculado que me muestre un texto que dice que no hay airbnb.
 
 he creado una cuarta hoja que me servira para la descripcion emergente de la tercera hoja y mostrar el promedio del precio total.
 
 en el dashboard he juntado las tres vistas y he usado como filtro la primera hoja para que al pinchar en cualquiera de los barrios cambien las demas hojas en funcion de el barrio elegido.
