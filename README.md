# Práctica tableau

La pregunta para comenzar la práctica ha sido la de mostrar los 10 barrios de Madrid con un promedio del precio más la tarifa de limpieza más bajo.

En la primera hoja he filtrado por barrios, y he puesto un parámetro que se llama "Nº barrios" que muestra los 10 más baratos. También he aplicado el filtro para todas las hojas. He creado un campo calculado que hace el promedio de la suma del precio más la tarifa de limpieza, que es la medida que usaré para las vistas, y también he coloreado las barras con el número de reviews.

En la segunda hoja he creado una jerarquía con "tipo de propiedad" y "tipo de habitación", para que me muestre los tipos de habitación por el precio total.

En la tercera hoja he realizado un mapa para ver el nivel de precio según el código postal; he creado un campo calculado que me indica tres niveles de precios: baratos, precio medio y caros. Fácilmente podremos diferenciar cuál es el nivel. También he asociado otra hoja a la descripción para que me muestre el precio total por código postal y, como hay códigos postales que no tenía ningún Airbnb, he creado otro campo calculado que me muestre un texto que dice que no hay Airbnb.

He creado una cuarta hoja que me va a servir para la descripción emergente de la tercera hoja y mostrar el promedio del precio total.

En el dashboard he juntado las tres vistas y he usado como filtro la primera hoja, para que, al pinchar en cualquiera de los barrios, cambien las demás hojas en función del barrio elegido.
