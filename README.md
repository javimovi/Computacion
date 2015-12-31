# Desactivar la bomba

En la resolución de este simpático ejemplo aprenderemos a utilizar el lenguaje ensamblador, la numeración hexadecimal, a leer e interpretar un código ensamblador de un código fuente, a "hackear" un programa ejecutable para obtener las dos constraseñas ocultas y una de ellas con un cifrado que podremos descubrir y descrifrar.

Se trata de la implementación de un programa en C, que simula la explosión de una bomba si el usuario no introduce correctamente dos claves o si las introduce en un tiempo superior a 1 minuto. No es necesario que la bomba explote mientras el usuario está tecleando las claves; basta con que lo haga después de introducir la clave, si es entonces cuando se detecta que ha tardado demasiado tiempo.

Las claves serán una contraseña de entre 8 y 10 caracteres, y un código de entre 3 y 6 dígitos decimales. Para que se pueda pedir al usuario la segunda clave, éste debe haber acertado ya la primera en el tiempo estipulado.

La resolución del problema se basa en conseguir las dos claves a traves del ejecutable del programa sin usar el código fuente, para ello obtenemos el lenguaje ensamblador y desciframos cuales son las operaciones que se realizan y cuales son las claves, ya que estas tienen un cifrado especial.

Para resolver este problema, trabajaremos en Ubuntu y tendremos que tener instalado el programa ddd que nos muestra de un ejecutable su código ensamblador, necesitaremos entender el código ensamblador y la numeración hexadecimal.

Este es un problema libre resuelto por mi para la asignatura Estructura de Computación de la UGR.


