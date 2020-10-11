## Ejercicio 1
La aplicación elegida ha sido la aplicación creada para la asignatura **Programación Web**, en ella se implementa un gestor de bases de datos, concretamente un gestor de bibliotecas. Su arquitectura es una arquitectura por capas, donde se pueden destacar las siguientes:

-Capa de almacenamiento
-Capa lógica
-Capa de presentación

La capa de almacenamiento consta de un sistema gestor de bases de datos, concretamente SQL, que gestiona la creación, alamcenamiento y modificación de bibliotecas del sistema, que pueden ser definidas por el usuario en la capa de presentación y cuya lógica se localiza en la capa del mismo nombre.

Por otro lado, la capa lógica, que es el núcleo de la aplicación, es la encargada de recibir las peticiones de la capa de presentación y comunicarse con la capa de almacenamiento para responder a las mismas. Esta capa se encuentra programada en *PHP*.

Finalmente, la capa de presentación, creada con *HTML* y *CSS*, recibe las peticiones del usuario y muestra los cambios que se realizan tras esta en este nivel.

### Evolución a microservicios
Para que esta aplicación avance a una arquitectura por microservicios, podría realizarse un microservicio dedicado exclusivamente al almacenamiento y base de datos y otro dedicado exclusivamente a la presentación mediante algún framework y empleando un lenguaje moderno.