Marcos Eduardo Garcia A01276213
Marcela Ibarra A01231973
Jesús David Talamantes Morales A01706335

Este paquete utiliza tf2 y el concepto de transformaciones para mejorar el ejemplo utilizado 
dentro de los tutoriales de ROS. En esta implementacion, se puede manejar a una tortuga y una segunda la sigue y la tercer tortuga sigue a la segunda tortuga. Dentro de los nodos principales se crean publisher y listener ademaás se crea un nodo para contar el número de colisiones de las tortugas cuando chocan con alguno de los bordes.

Para conseguir la visualizacion de los choques se ejecuta lo siguiente en una terminal

1.- rostopic echo turtle!/collision


