# Act1_U2-Abstract-Factory
Actividad de evidencia 1_U2 Abstract Factory

Gabriel San Roman Castillo - 19211731

## [Portada](./Portada%20Abstract%20Fact.pdf)

## Introducción 
Patron creacional

Nos permite producir familias de objetos relacionados sin especificar sus clases concretas.

Proporciona una interfaz para crear familias de objetos relacionados o dependientes sin 
especificar sus clases concretas. En lugar de crear un solo producto, este patrón asegura 
que todos los productos creados por una misma fábrica sean compatibles entre sí.

Lo primero que sugiere el patrón Abstract Factory es que declaremos de forma explícita interfaces 
para cada producto diferente de la familia de productos. Después podemos hacer que todas las 
variantes de los productos sigan esas interfaces

Palabra Clave: Familias

## [Codigo](Program.cs)

## Conclusion

El uso de Abstract Factory nos deja hacer modulos donde podemos encapsular la creacion de los objetos 
y delegandolo a las fabricas para evitar varios new por todo el copdigo.
Y tambien se pudo ver como podemos extender el codigo agregando nuevas modalidades(clases) sin alterar la que ya estaban.
