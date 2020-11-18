CHAT ESTAMBRADO
En esta práctica mostraremos cómo hacer un chat cliente-servidor a partir de sockets e hilos en Java.

\*Contenido*/
Este proyecto contiene dos ramas: cliente y servidor. 

Dentro del paquete cliente se encuentran las clases con los hilos (Uno que envía los mensajes y otro que los recibe) y la interfaz gráfica del cliente.

Por otro lado, se encuentra el paquete del servidor que contiene una clase con hilos (Se encarga de recibir los mensajes) y su interfaz gráfica

\*Instalación*/
Para ejecutar este proyecto, es necesario correr la clase principalChat primero, ya que esta incializara nuestro servidor e instanciara la ip. En esta interfaz solo se podran ver los
mensaje que el cliente mande.

Como siguiente paso, se deberá correr la clase clienteChat para que el cliente pueda establecer los mensajes con la respectiva ip y con su respectivo usuario. En esta interfaz 
se podran mandar como recibir mensajes de otros clientes.

