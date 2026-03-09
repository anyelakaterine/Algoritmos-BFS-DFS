Implementación de BFS y DFS en Python

Presenta: “Anyela Katerine Rentería Cuama”

Este proyecto implementa dos algoritmos clásicos de búsqueda en grafos utilizando Python:
•	BFS (Breadth First Search) – Búsqueda en anchura
•	DFS (Depth First Search) – Búsqueda en profundidad
El código fue desarrollado y ejecutado en Google Colab, donde también se muestra de forma gráfica el grafo utilizado.
Objetivo
El objetivo de este proyecto es programar e implementar los algoritmos BFS y DFS sobre un grafo pequeño y comparar sus resultados en términos de:
•	Camino encontrado entre un nodo inicial y uno final.
•	Memoria utilizada durante la ejecución del algoritmo.

Descripción del problema
Se utiliza un grafo compuesto por varios nodos conectados entre sí.
Cada nodo representa un punto dentro del grafo y cada conexión representa una relación entre nodos.
El programa busca encontrar un camino desde un nodo origen hasta un nodo destino utilizando dos métodos diferentes de búsqueda.
Algoritmos implementados
BFS (Breadth First Search)
BFS es un algoritmo de búsqueda que explora el grafo por niveles.

Características:
•	Utiliza una cola (FIFO – First In First Out).
•	Primero explora los nodos más cercanos al nodo inicial.
•	Garantiza encontrar el camino más corto en grafos no ponderados.
DFS (Depth First Search)
DFS es un algoritmo que explora el grafo en profundidad.

Características:
•	Utiliza una pila (LIFO – Last In First Out).
•	Sigue un camino hasta el final antes de explorar otros caminos.
•	Puede encontrar soluciones rápidamente en estructuras profundas.

Funcionamiento del programa
El programa realiza los siguientes pasos:
1.	Define un grafo pequeño utilizando un diccionario en Python.
2.	Implementa la función BFS para encontrar un camino entre dos nodos.
3.	Implementa la función DFS para encontrar un camino entre dos nodos.
4.	Muestra el camino encontrado por cada algoritmo.
5.	Calcula una estimación de la memoria utilizada.
6.	Muestra una comparación de resultados entre ambos algoritmos.
7.	Dibuja el grafo de forma gráfica para visualizar los nodos y conexiones.

Resultados
El programa muestra:
•	El camino encontrado por BFS
•	El camino encontrado por DFS
•	El uso estimado de memoria
•	Una tabla comparativa de resultados
Esto permite analizar cómo funcionan los algoritmos de búsqueda sobre grafos.

