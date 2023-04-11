# mongodb-workshop

## Exercise 2

1.  Mostrar todos los documentos de la colección restaurantes
2.  Mostrar los campos restaurant_id, nombre, distrito y cocina, pero excluya el campo \_id para todos los documentos de la colección restaurantes
3.  Mostrar los primeros 5 restaurantes que se encuentran en el distrito Bronx
4.  Devolver los restaurantes que lograron una puntuación superior a 80 pero inferior a 100
5.  Devolver los restaurantes que se ubican en un valor de latitud inferior a -95.754168
6.  Devolver los restaurantes que no preparan cocina americana y lograron una puntuación superior a 70 y se ubicaron en una longitud inferior a -65.754168. Nota: Realice esta consulta sin usar el operador $and
7.  Devolver los restaurantes que no preparan cocina americana y lograron un punto de calificación 'A' que no pertenece al distrito de Brooklyn. El documento debe mostrarse según la cocina en orden descendente.
8.  Devolver los restaurantes que pertenecen al distrito Bronx y preparan platos americanos o chinos
9.  Devolver ID del restaurante, nombre, distrito y la cocina para aquellos restaurantes que pertenecen al distrito de Staten Island o Queens o Bronx o Brooklyn
10. Devolver ID del restaurante, nombre, distrito y la cocina de aquellos restaurantes que lograron una puntuación que no supere los 10
11. Devolver ID del restaurante, el nombre y las calificaciones del restaurante para aquellos restaurantes que obtuvieron una calificación de "A" y obtuvieron un puntaje de 11 en una fecha ISO "2014-08-11T00: 00: 00Z" entre muchas fechas de encuesta
12. Devolver ID del restaurante, nombre, dirección y ubicación geográfica del restaurante de aquellos donde el segundo elemento de la matriz coord contiene un valor que es más de 42 y hasta 52
13. Crea un par de restaurantes que te gusten. Tendrás que buscar en Google Maps los datos de las coordenadas
14. Actualiza los restaurantes. Cambia el tipo de cocina 'Ice Cream, Gelato, Yogurt, Ices' por 'sweets'
15. Actualiza nombre del restaurante 'Wild Asia' por 'Wild Wild West'
16. Borra los restaurantes con latitud menor que -95.754168

## Find

https://www.mongodb.com/docs/manual/reference/method/db.collection.findOne/
https://www.mongodb.com/docs/manual/reference/method/db.collection.find/

[CURSOR](https://www.mongodb.com/docs/manual/tutorial/iterate-a-cursor/#std-label-read-operations-cursors)

[OPERATOR](https://www.mongodb.com/docs/manual/reference/operator/query/)

## Cursor methods

https://www.mongodb.com/docs/manual/reference/method/cursor.skip/
https://www.mongodb.com/docs/manual/reference/method/cursor.limit/
https://www.mongodb.com/docs/manual/reference/method/cursor.sort/
https://www.mongodb.com/docs/manual/reference/method/cursor.count/
https://www.mongodb.com/docs/manual/reference/method/cursor.toArray/

## Insert

https://www.mongodb.com/docs/manual/reference/method/db.collection.insertOne/
https://www.mongodb.com/docs/manual/reference/method/db.collection.insertMany/

## Update

https://www.mongodb.com/docs/manual/reference/method/db.collection.updateOne/
https://www.mongodb.com/docs/manual/reference/method/db.collection.updateMany/

## Delete

https://www.mongodb.com/docs/manual/reference/method/db.collection.deleteOne/
https://www.mongodb.com/docs/manual/reference/method/db.collection.deleteMany/
