# Binary Search: An Efficient Algorithm for Searching in an Ordered List

This code implements the binary search algorithm for efficiently searching for an element in an ordered list. The algorithm repeatedly divides the list in half and determines which half the target element is in, discarding the other half in each iteration. Binary search has a time complexity of O(log n), which makes it much faster than naive search, which has a time complexity of O(n).

The code begins by defining two functions: `busqueda_ingenua` and `busqueda_binaria`. The first is a simple linear search that iterates through each element of the list in order until it finds the target or reaches the end of the list. The second is the implementation of the binary search. It takes three arguments: the list to search, the target to find, and the lower and upper limits of the current sublist. If limits are not provided, they are automatically set as the first and last element of the list.

After defining the functions, the code creates an ordered list of 1 million random numbers and measures the time it takes to perform a naive search and a binary search on the list. The naive search is commented out because it is much slower and not practical for such a large list. The binary search is much faster and finds the target in the list in a fraction of the time.

Overall, this code demonstrates how binary search can be a more efficient option for searching for elements in an ordered list compared to naive search. It also showcases the usefulness of programming for problem-solving and increasing the efficiency of algorithms.


# Búsqueda binaria: Un algoritmo eficiente para buscar en una lista ordenada

Este código implementa el algoritmo de búsqueda binaria para buscar un elemento en una lista ordenada de forma eficiente. El algoritmo divide repetidamente la lista en dos mitades y determina en qué mitad se encuentra el elemento objetivo, descartando la otra mitad en cada iteración. La búsqueda binaria tiene una complejidad de tiempo de O(log n), lo que lo hace mucho más rápido que la búsqueda ingenua, que tiene una complejidad de tiempo de O(n).

El código comienza definiendo dos funciones: `busqueda_ingenua` y `busqueda_binaria`. La primera es una búsqueda lineal simple que recorre cada elemento de la lista en orden hasta encontrar el objetivo o llegar al final de la lista. La segunda es la implementación de la búsqueda binaria. Toma tres argumentos: la lista a buscar, el objetivo a encontrar y los límites inferior y superior de la sublista actual. Si no se proporcionan límites, se establecen automáticamente como el primer y último elemento de la lista.

Después de definir las funciones, el código crea una lista ordenada de 1 millón de números aleatorios y mide el tiempo que tarda en realizar una búsqueda ingenua y una búsqueda binaria en la lista. La búsqueda ingenua se comenta porque es mucho más lenta y no es práctica para una lista tan grande. La búsqueda binaria es mucho más rápida y encuentra el objetivo en la lista en una fracción del tiempo.

En general, este código muestra cómo la búsqueda binaria puede ser una opción más eficiente para buscar elementos en una lista ordenada en comparación con la búsqueda ingenua. Además, demuestra la utilidad de la programación para resolver problemas y aumentar la eficiencia de los algoritmos.
