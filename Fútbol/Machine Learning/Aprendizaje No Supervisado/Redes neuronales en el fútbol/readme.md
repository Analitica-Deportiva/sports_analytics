El objetivo de este articulo principalmente es evaluar si las estadísticas de juego de los futbolistas 
(centrándose inicialmente en las métricas de pase) reflejan de forma automática sus posiciones reales en el campo de juego.

Para lograrlo, se implementa una arquitectura basada en Mapas Autoorganizados (SOM) combinada con un algoritmo de Clustering Jerárquico (método Ward). 
Toda la lógica de procesamiento, modelado y reducción de dimensionalidad (mediante PCA) se desarrolló en el lenguaje de programación R, utilizando el paquete `kohonen`. 

Adicionalmente, el proyecto incluye una plataforma web interactiva y reactiva desarrollada con Shiny, la cual permite parametrizar el modelo en tiempo real 
(ajustando iteraciones, dimensiones del mallado y número de clústers) y visualizar de manera dinámica el impacto en las agrupaciones de los jugadores.
