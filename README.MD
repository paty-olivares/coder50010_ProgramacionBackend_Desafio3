DESAFIO 3: Servidores con express
OBJETIVO: Desarrollar un servidor basado en express donde podamos hacer consultas a nuestro archivo de productos.

Patricia Olivares - 16/12/2023

ENTREGABLE:
Se instalaron las dependencias a partir del comando npm install
npm start - arranca el servidor
products.json - Archivo de Productos
Se configuró el servidor para que esté corriendo en el puerto 8080.
Escenarios de Test: 
 -> Ejecute la url http://localhost:8080/products sin query, eso debe devolver todos los 10 productos.
 -> Ejecute la url http://localhost:8080/products?limit=5 , eso debe devolver sólo los primeros 5 de los 10 productos.
 -> Ejecute la url http://localhost:8080/products/4, eso debe devolver sólo el producto con id=2.
 -> Ejecute la url http://localhost:8080/products/89, al no existir el id del producto, debe devolver un objeto con un error indicando que el producto no existe.
