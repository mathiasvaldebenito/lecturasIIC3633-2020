# Crítica: Post original FunkSVD

El blog trata sobre cómo el autor y su equipo lograron el tercer puesto en la competencia _netflix prize_. La competencia trataba en crear un modelo que generara
recomendaciones de películas a usuarios de la plataforma de Netflix, en el cual los datos que se entregaban eran 100M ratings de 17K películas hechas por 500K
usuarios. A lo largo del blog se explica la matemática concerniente al cálculo de la predicción del rating de una pelicula que un usuario X no ha visto, pero del
cual se tiene cierta información respecto a sus preferencias en base a otros ratings.

Uno de los aspectos interesantes del blog es que debido a ser un blog y no un texto estrictamente académico, el autor se da ciertas libertades al momento de
escribir, como lo pueden ser la falta rigurosidad matemática que uno esperaría, por ejemplo, de un paper. Sin embargo, esto le da otro encanto, pues va directo al
grano de cómo fueron las cosas sin hacer rodeos innecesarios muchas veces. Siguiendo esta linea, existen obvios aspectos negativos que conlleva esta falta de
rigurosidad como lo son aquellas ocasiones en dónde solo se decanta por elegir valores que obtuvo a través de la experimentación que _fortuitamente_ resultaron
ser mejores. Ejemplo de esto son: "Lrate is the learning rate, a rather arbitrary number which I fortuitously set to 0.001 on day one and regretted it every time
I tried anything else after that" y "But in fact K=25 seems to work well so I used that instead. :)".

Otro aspecto negativo son los gráficos utilizados en la última parte del blog a modo de mostrar resultados, sinceramente no entendí qué representaban estos
gráficos y lo que estos apuntaban a demostrar.
