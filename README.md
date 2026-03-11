Implementación de algoritmos BFS y DFS en Python

Autor: Anyela Katerine Rentería Cuama

Este proyecto presenta la implementación de dos algoritmos fundamentales de búsqueda en grafos:

BFS (Breadth First Search) – Búsqueda en anchura
DFS (Depth First Search) – Búsqueda en profundidad
El desarrollo del código se realizó en Google Colab, donde se ejecuta el algoritmo y se visualiza el grafo utilizado para el ejercicio.

1. Introducción
En informática y especialmente en el área de inteligencia artificial, los algoritmos de búsqueda permiten explorar estructuras de datos complejas con el fin de encontrar soluciones a diferentes problemas.

Una de las estructuras más utilizadas para representar estos problemas son los grafos, los cuales están compuestos por nodos (vértices) y aristas (conexiones entre nodos).

En este proyecto se implementan dos algoritmos clásicos utilizados para recorrer grafos:

Búsqueda en anchura (BFS)
Búsqueda en profundidad (DFS)
Ambos algoritmos permiten explorar un grafo desde un nodo inicial hasta encontrar un nodo objetivo.

2. Objetivo del proyecto
El objetivo de este trabajo es implementar los algoritmos BFS y DFS en Python y analizar su comportamiento al buscar un camino dentro de un grafo.

Los objetivos específicos son:

Implementar ambos algoritmos de búsqueda.
Encontrar un camino entre un nodo inicial y un nodo destino.
Comparar el camino encontrado por cada algoritmo.
Analizar el uso aproximado de memoria durante la ejecución.
Visualizar el grafo utilizado en el ejercicio.
3. Descripción del problema
Para el desarrollo del ejercicio se utiliza un grafo pequeño compuesto por varios nodos conectados entre sí.

Cada nodo representa un punto dentro del sistema y cada conexión representa una posible relación entre nodos.

El grafo se define en Python mediante un diccionario, donde cada nodo contiene una lista de nodos adyacentes.

El problema consiste en encontrar una ruta que permita ir desde un nodo origen hasta un nodo destino utilizando diferentes estrategias de búsqueda.

4. Algoritmos implementados
4.1 Breadth First Search (BFS)
El algoritmo BFS explora el grafo por niveles, comenzando desde el nodo inicial y visitando primero todos los nodos vecinos antes de continuar con los niveles siguientes.

Características principales

Utiliza una cola (FIFO – First In First Out).
Explora primero los nodos más cercanos al nodo inicial.
Garantiza encontrar el camino más corto en grafos no ponderados.
4.2 Depth First Search (DFS)
El algoritmo DFS explora el grafo en profundidad, avanzando por un camino hasta llegar al final antes de retroceder y explorar otras posibles rutas.

Características principales

Utiliza una pila (LIFO – Last In First Out).
Explora completamente un camino antes de intentar otro.
Permite recorrer todas las posibles rutas dentro del grafo.
5. Funcionamiento del programa
El programa desarrollado sigue los siguientes pasos:

Se define un grafo utilizando un diccionario en Python.
Se implementa la función correspondiente al algoritmo BFS.
Se implementa la función correspondiente al algoritmo DFS.
Se ejecutan ambos algoritmos utilizando el mismo nodo inicial y nodo destino.
Se obtiene el camino encontrado por cada algoritmo.
Se calcula una estimación del uso de memoria durante la ejecución.
Se presentan los resultados obtenidos para comparar el comportamiento de ambos métodos.
6. Resultados obtenidos
Al ejecutar el programa se obtienen los siguientes resultados:

El camino encontrado utilizando BFS.
El camino encontrado utilizando DFS.
Una estimación del uso de memoria durante la ejecución.
Una comparación entre ambos algoritmos.
7. Tecnologías utilizadas
Para el desarrollo de este proyecto se utilizaron las siguientes herramientas:

Python
Google Colab
GitHub
8. Acceso al código del proyecto
El código completo desarrollado para este trabajo se encuentra disponible en el siguiente repositorio:

https://github.com/anyelakaterine/Algoritmos-BFS-DFS/tree/main/TP

En este enlace se puede acceder al notebook que contiene la implementación de los algoritmos BFS y DFS.

