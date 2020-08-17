# Crítica: Item-Based Collaborative Filtering Recommendation Algorithms

Este paper trata fundamentalmente sobre la comparación de diferentes algoritmos de generación de recomendaciones basados
en items y algoritmos clásicos del área de sistemas recomendadores como lo son los algoritmos de _collaborative filtering_, entre
ellos destacando: Bayesian networks, clustering, Horting y K Nearest Neighbors. El objetivo al que apunta el paper es a resolver dos desafíos que son
opuestos el uno con el otro: escalabilidad de los algoritmos de _collaborative filtering_ y la calidad de las recomendaciones
 estos mismos generan. Para lo anterior, se realizan variados experimentos poniendo a prueba un algoritmo de generación de recomendaciones basados
 en items contra  un algoritmo ampliamente utilizados como K Nearest Neighbors.

Me parece importante destacar el año en que fue publicado este paper: *2001*. Dado que en aquel tiempo no se disponían de las herramientas de las que hoy se hace,
es interesante leer cómo se intentaba sortear problemáticas como lo podían ser el espacio en memoria y la performance en tiempo del equipo. Para hacer la
comparación más visual basta con ver el equipo dónde se realizaron los experimentos: "linux based PC with Intel Pentium III processor having a speed of 600 MHz
and 2GB of RAM". Dado este contexto, es lógico buscar formas de aligerar la carga de procesamiento que debe realizar el computador y reducit el espacio en memoria
que este debe utilizar para resolver el problema.

Por otro lado, un aspecto negativo fue la falta de un test de validación para el ajuste de los parámetros del modelo. Se usó una separación de 80% para el set
de entrenamiento y 20% del set de test, en este caso un 80% de los datos destinado solo al set de entrenamiento me parece excesivo y puede llevar a un overfitting
del modelo. Hubiera sido más correcto dedicar un 60% al set de entrenamiento, el mismo 20% al set de test y el restante 20% a un set de validación, de esta forma
se habría evitado espacios a la duda de los resultados del modelo.
