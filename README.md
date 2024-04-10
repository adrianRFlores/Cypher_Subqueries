# Cypher_Subqueries

Query existencial simple, sin subquery.
Devuelve a las personas que trabajan para Neo4j y sus amigos.
![cs1](https://github.com/adrianRFlores/Cypher_Subqueries/assets/84111818/f1fb1b3d-0050-4223-9349-6966ba4f41ed)

El mismo query existencial, esta vez con subqueries
![cs2](https://github.com/adrianRFlores/Cypher_Subqueries/assets/84111818/b1405980-8f7e-4c6e-96bd-2924cd0b81d8)

Otro query existencial con subqueries, esta vez un poco más complejo.  
El subquery dentro de EXISTS contiene otro subquery, esta vez con COUNT.  
Esta consulta devuelve las personas con 3 o más tecnologías con LIKE y que trabajan para cualquier empresa cuyo nombre empiece con 'Company'.
![cs3](https://github.com/adrianRFlores/Cypher_Subqueries/assets/84111818/fad13bb7-04cd-4c6c-b4c1-fb013f9c2201)

Query que utiliza la cláusula CALL.  
Este subquery busca la unión entre las personas que les gusta Java y las personas que tienen más de un amigo.  
La cláusula CALL devuelve el resultado, el cual es utilizado en el query principal
![cs4](https://github.com/adrianRFlores/Cypher_Subqueries/assets/84111818/6a103ae0-cc0b-4de2-b25e-fff7ca8a22a0)

Query similar al anterior, con la cláusula CALL.  
La diferencia entre estos es que, luego del subquery, todavía se realiza un poco más de manipulación del resultado.  
El resultado de la consulta principal se ordena de manera descendente
![cs5](https://github.com/adrianRFlores/Cypher_Subqueries/assets/84111818/88317b9e-1e03-487c-b421-562614b7dcb2)
