# Algoritmos de búsqueda en Inteligencia Artificial

## 1. Problemas de búsqueda

Un problema de búsqueda consiste en encontrar una secuencia de acciones que permita pasar de una situación inicial a una situación deseada. Para resolverlo, se deben definir los estados posibles, las acciones disponibles, las condiciones que determinan el objetivo y el costo de las acciones, cuando corresponda. Estos problemas se utilizan en inteligencia artificial para resolver laberintos, planificar rutas y tomar decisiones.

Referencia: Russell y Norvig (2021).

## 2. Espacio de estados

El espacio de estados es el conjunto de todas las situaciones posibles que pueden presentarse durante la resolución de un problema. Cada estado representa una configuración específica del sistema, y las acciones permiten pasar de un estado a otro. Explorar este espacio ayuda a encontrar una secuencia de movimientos que conduzca al objetivo.

Referencia: Russell y Norvig (2021).

## 3. Estado inicial

El estado inicial es la situación desde la cual comienza el proceso de búsqueda. Representa las condiciones en las que se encuentra el problema antes de realizar cualquier acción. A partir de este estado, el algoritmo genera nuevos estados hasta encontrar uno que cumpla con la meta establecida.

Referencia: Russell y Norvig (2021).

## 4. Acciones

Las acciones son los movimientos, operaciones o decisiones que un agente puede ejecutar desde un estado determinado. Cada acción permite generar uno o varios estados sucesores, dependiendo de las reglas del problema. Por ejemplo, en un laberinto, las acciones pueden ser moverse hacia arriba, abajo, izquierda o derecha.

Referencia: Russell y Norvig (2021).

## 5. Modelo de transición

El modelo de transición describe el resultado de ejecutar una acción desde un estado específico. Permite determinar a qué nuevo estado se llegará después de realizar una acción. Es importante porque establece las reglas que conectan los diferentes estados y permite al algoritmo construir las posibles rutas hacia la solución.

Referencia: Russell y Norvig (2021).

## 6. Prueba de meta

La prueba de meta es el procedimiento que verifica si un estado alcanzado cumple con las condiciones necesarias para considerar resuelto el problema. Cada vez que el algoritmo examina un estado, puede comprobar si satisface el objetivo. Si la prueba es positiva, se ha encontrado una solución; de lo contrario, la búsqueda continúa.

Referencia: Russell y Norvig (2021).

## 7. Costo del camino

El costo del camino es el valor total asociado a una secuencia de acciones desde el estado inicial hasta un estado determinado. Se calcula sumando los costos individuales de cada acción. Puede representar distancia, tiempo, dinero o recursos utilizados. Este concepto es fundamental en algoritmos como la búsqueda de costo uniforme, que busca una solución de costo mínimo.

Referencia: Russell y Norvig (2021).

## 8. Solución

Una solución es una secuencia de acciones que permite llegar desde el estado inicial hasta un estado que cumple con la prueba de meta. Dependiendo del problema, puede existir una sola solución o varias alternativas. En algunos casos, no basta con encontrar una solución, sino que también se busca la que tenga el menor costo.

Referencia: Russell y Norvig (2021).

## 9. Frontera

La frontera es el conjunto de nodos que ya fueron generados durante la búsqueda, pero que todavía no han sido explorados o expandidos. El algoritmo selecciona un nodo de esta frontera según su estrategia de búsqueda. Su organización depende del método utilizado: una cola para amplitud, una pila para profundidad o una cola de prioridad para costo uniforme.

Referencia: University of California, Berkeley (s. f.).

## 10. Nodo

Un nodo es una estructura que representa un estado dentro del proceso de búsqueda. Además del estado, normalmente almacena información como el nodo padre, la acción que permitió llegar a él, la profundidad y el costo acumulado del camino. Estos datos permiten reconstruir la ruta seguida para alcanzar una solución.

Referencia: University of California, Berkeley (s. f.).

## 11. Agente de resolución

Un agente de resolución de problemas es un sistema inteligente que determina qué acciones debe realizar para alcanzar un objetivo. Primero formula el problema, identifica el estado inicial y la meta, y después utiliza un algoritmo de búsqueda para encontrar una secuencia de acciones adecuada. Su propósito es resolver el problema de manera organizada y, cuando corresponde, minimizar los costos.

Referencia: Russell y Norvig (2021).

## 12. Sistemas de búsqueda ciega

Los sistemas de búsqueda ciega son métodos que exploran el espacio de estados sin utilizar información heurística que indique qué tan cerca se encuentra un estado de la meta. Se basan en la información básica del problema, como las acciones disponibles, el estado inicial y la prueba de meta. Entre los principales algoritmos se encuentran la búsqueda en amplitud, la búsqueda en profundidad y la búsqueda de costo uniforme.

Referencia: University of California, Berkeley (s. f.).

## 13. Búsqueda no informada o ciega

La búsqueda no informada es una estrategia de inteligencia artificial que no utiliza estimaciones sobre la distancia o dificultad restante para alcanzar el objetivo. En su lugar, decide qué estado explorar utilizando reglas como la profundidad del nodo o el costo acumulado del camino. Aunque puede encontrar soluciones sin conocimiento adicional, en problemas grandes puede requerir mucho tiempo y memoria.

Referencia: University of California, Berkeley (s. f.).

## 14. Búsqueda en amplitud (BFS)

La búsqueda en amplitud explora primero los estados más cercanos al estado inicial. Visita todos los nodos de un nivel antes de continuar con el siguiente, utilizando una cola FIFO para mantener el orden de exploración. Es completa cuando el factor de ramificación es finito y encuentra una solución de menor número de pasos cuando todas las acciones tienen el mismo costo.

Referencia: University of California, Berkeley (s. f.).

## 15. Búsqueda en profundidad (DFS)

La búsqueda en profundidad explora una rama del árbol hasta alcanzar un punto en el que no puede continuar y, entonces, retrocede para examinar otras alternativas. Utiliza una pila LIFO, que da prioridad al nodo agregado más recientemente. Puede consumir menos memoria que la búsqueda en amplitud, pero no garantiza encontrar una solución en espacios infinitos ni la solución de menor costo.

Referencia: University of California, Berkeley (s. f.).

## 16. Búsqueda de costo uniforme (UCS)

La búsqueda de costo uniforme selecciona para explorar el nodo cuyo camino desde el estado inicial tiene el menor costo acumulado. Para hacerlo, utiliza una cola de prioridad ordenada según el costo de cada camino. Es completa bajo las condiciones habituales de costos de paso positivos y, con costos no negativos, garantiza una solución de costo mínimo cuando se implementa correctamente.

Referencia: University of California, Berkeley (s. f.).

## 17. Cola

Una cola es una estructura de datos que funciona bajo el principio FIFO (First In, First Out), que significa que el primer elemento en entrar es el primero en salir. Los elementos se agregan al final y se retiran desde el principio. En los algoritmos de búsqueda, esta estructura permite explorar los nodos en el mismo orden en que fueron agregados, como ocurre en la búsqueda en amplitud.

Referencia: University of California, Berkeley (s. f.).

## 18. Pila

Una pila es una estructura de datos que funciona bajo el principio LIFO (Last In, First Out), es decir, el último elemento en entrar es el primero en salir. Los elementos se agregan y retiran desde el mismo extremo. En la búsqueda en profundidad, permite explorar primero los nodos más recientemente generados y avanzar por una rama antes de regresar a otras alternativas.

Referencia: University of California, Berkeley (s. f.).

## 19. Completitud

La completitud es una propiedad que indica si un algoritmo de búsqueda garantiza encontrar una solución cuando existe, siempre que se cumplan determinadas condiciones. Por ejemplo, la búsqueda en amplitud es completa cuando el factor de ramificación es finito, mientras que la búsqueda en profundidad puede quedarse explorando indefinidamente una rama sin solución.

Referencia: University of California, Berkeley (s. f.).

## 20. Optimalidad

La optimalidad es la capacidad de un algoritmo para garantizar que la solución encontrada tiene el menor costo posible entre todas las soluciones disponibles. No todos los algoritmos de búsqueda son óptimos. La búsqueda en amplitud lo es cuando todos los pasos tienen el mismo costo, mientras que la búsqueda de costo uniforme lo es cuando los costos de las acciones son no negativos y se cumplen las condiciones necesarias del algoritmo.

Referencia: University of California, Berkeley (s. f.).

## 21. Complejidad en tiempo

La complejidad en tiempo describe cómo aumenta el trabajo computacional de un algoritmo conforme crece el tamaño del problema. En los algoritmos de búsqueda, suele analizarse mediante la cantidad de nodos que pueden generarse o explorarse en el peor caso. Por ejemplo, la búsqueda en amplitud puede explorar una cantidad exponencial de nodos según la profundidad de la solución.

Referencia: University of California, Berkeley (s. f.).

## 22. Complejidad en espacio

La complejidad en espacio indica cuánta memoria necesita un algoritmo durante su ejecución. En la búsqueda, incluye la memoria utilizada para almacenar la frontera y, según la implementación, los nodos visitados y la información necesaria para reconstruir el camino. La búsqueda en amplitud suele requerir mucha memoria porque mantiene numerosos nodos pendientes, mientras que la búsqueda en profundidad generalmente necesita menos.

 Referencia: University of California, Berkeley (s. f.).

