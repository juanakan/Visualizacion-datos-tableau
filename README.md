# Practica tableau

La pregunta para comenzar la practica ha sido la de mostrar los barrios de Madrid con un promedio del precio más la tarifa de limpieza más bajo ademas de pintar las barras para ver los que tienen más reviews.

En la primera hoja, he filtrado por barrios y he puesto un parámetro que se llama Nº barrios que muestra los 10 más baratos, también he aplicado el filtro para todas las hojas. He creado un campo calculado que me hace el promedio de la suma del precio más la tarifa de limpieza que es la medida que usare para las vistas.

En la segunda hoja he creado una jerarquía con tipo de propiedad y tipo de habitación para que me muestre los tipos por el precio total también lo he filtrado por el tipo de propiedad

En la tercera hoja he realizado un mapa para ver el nivel de precio según el código postal donde he creado un campo calculado que me indica tres niveles de precios: baratos, precio medio y caros. Fácilmente podremos diferenciar cual es el nivel. También he asociado otra hoja a la descripción para que me muestre el precio total por código postal y como hay códigos postales que no tenía ningún Airbnb he creado otro campo calculado que me muestre un texto que dice que no hay Airbnb.

He creado una cuarta hoja que me va a servir para la descripción emergente de la tercera hoja y mostrar el promedio del precio total.

En el dashboard he juntado las tres vistas y he usado como filtro la primera hoja para que al pinchar en cualquiera de los barrios cambien las demas hojas en función de el barrio elegido.
