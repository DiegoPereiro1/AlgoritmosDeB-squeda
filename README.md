# Ejercicio Coste uniforme


En la captura se pueden ver las dos rutas obtenidas con el menor costo hasta calatayud y una tercera que no llega a terminar en calatayud ya que los nodos que exploraría ya se habían explorado con un coste menor.

![wewqeqwe](https://github.com/DiegoPereiro1/AlgoritmosDeB-squeda/assets/150299123/61ef304e-566b-44e0-8195-3b111bd24d08)






# Ejercicio NPC
En la primera imagen se observa la primera rama del arból en la cual por orden alfabetico se puede ver que llega a la segunda ruta más óptima a la meta, con una heuristica de 32.
![Captura de pantalla de 2024-03-05 12-25-22 png](https://github.com/DiegoPereiro1/AlgoritmosDeB-squeda/assets/150299123/52dcecab-ebcf-4a05-806d-931d352f0998)

En esta segunda imagen se puede ver que se llega a la meta por la ruta más óptima con una heuristica de 28.
![Captura de pantalla de 2024-03-05 12-25-48 png](https://github.com/DiegoPereiro1/AlgoritmosDeB-squeda/assets/150299123/93739ee5-0e17-4162-b1c5-42f79b1afe65)

Para obtener las demás rutas se seguiría operando cogiendo el nodo abierto con la euristica más baja y en caso de que dos compartan la misma heurística se escogería el nodo abierto con más antigüedad.

