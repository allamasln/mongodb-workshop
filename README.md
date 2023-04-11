# mongodb-workshop

## Exercise 1

1.  Crea una nueva BD en Mongo que permita almacenar un listado de Contactos de una agenda. De cada contacto tenemos su nombre, podemos tener 3 teléfonos (uno de ellos como mínimo) y hasta dos emails (ninguno obligatorio). Crea al menos 5 contactos con combinaciones diferentes de los datos.
2.  Obten un contacto a partir de un email usando filtros.
3.  Crea una nueva BD que permita almacenar los datos de Autores y Libros (Autores tienen como datos el nombre, apellidos, año de nacimiento y el tipo de libros que escribe. Libros disponen de título, ISBN, tipo y número de páginas), puede que alguno de los datos no estén disponibles, pero los autores tienen que tener apellidos sí o sí y los libros el ISBN. Inserta al menos 5 autores y 5 libros y relaciónalos analizando los patrones de busqueda.
4.  Obten un autor filtrando por apellidos y un libro filtrando por ISBN.

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
