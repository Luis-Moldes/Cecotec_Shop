# Cecotec_Shop

Se trata de una web de compercio virtual simple desarrollada con Django, simulando una tienda de Cecotec. 


## Consideraciones Previas

-Para mayor facilidad de uso, se ha incluido en el proyecto un virtual environment, se recomienda hacer uso del mismo.

-El proyecto está pensado para ser lanzado en local. Para ello, se debe utilizar el comando "python manage.py runserver" en la terminal de Python.


## Guía de usuario

La web es muy básica, con su página principal mostrando los diferentes productos disponibles. Cada uno de ellos se puede añadir al carrito tantas veces comoo se desee. Accediendo al carrito el ususario puede consultar el total del pedido, así como variar las cantidades de cada uno de los productos. Una vez conforme, clickando a 'Finalizar Pedido' el ususario accede a una interfaz en la que insertar una serie de datos al respecto del pedido, los cuales, una vez insertados correctamente, permiten finalmente enviar el pedido, el cual es guardado en la base de datos SQL del proyecto. En caso de estar subida la web a un servidor web, ésta enviaría también un mail a todos los administradores de la misma (creados mediante el comando en la terminal "python manage.py createsuperuser") conteniendo toda la información proporcionada por el usuario.

A nivel de funcionamiento, toda la web se articula alrededor de la cookie 'Cart', la cual es la encargada de almacenar el pedido y todos sus cambios mientras el usuario se encuentre en la página. Gran parte del código para el apartado estético ha sido trasladado de proyectos anteriores.
