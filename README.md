# Console.log
La funcion integrada de Javascript console.log se utiliza para mostrar un mensaje en la consola, recibiendo como argumento uno o más objetos (mensajes o valores). Cada objeto se evalúa y se concatena en una string separada por espacios. Sirve para depurar y entender el comportamiento de sus códigos. Comprende un medio invaluable para comprender cómo se comporta el código en tiempo real.
## Ejemplos
Un ejemplo básico de esto podría ser: 
````
console.log("¡Hola, mundo!");
````

Otro más avanzado: 
````
const nombre = "Alice"; 
const edad = 28;
console.log("Nombre:", nombre, "Edad:", edad);
````

## Metodos
### console.error()
Muestra un mensaje de error. Se pueden utilizar sustituciones de cadenas y argumentos adicionales con este método.
### console.time()
Inicia un temporizador con un nombre especificado como parámetro. Hasta 10 000 temporizadores simultáneos pueden ejecutarse en una página determinada.
### console.warn()
Muestra un mensaje de advertencia. Puedes usar sustituciones de cadenas y argumentos adicionales con este método.
### console.trace()
Muestra una traza de pila.

# ¿Que contenido debemos publicar en la consola?  
## Consola del Front-end 
La consola del front-end se encuentra en el navegador del usuario. En esta se muestran mensajes que nos ayudan a ver qué pasa cuando el usuario interactúa con la aplicación, es decir, que nos muestran los errores por cada interacción. El Frontend se refiere a la parte visible de un sitio web o aplicación con la que los usuarios pueden interactuar directamente. Forma parte de las herramientas de desarrollo que están integradas en los navegadores web, accediendo a ellas a través de herramientas de desarrollador del navegador (DevTools). Sirve para manipular el DOM y CSS en tiempo real.
Un ejemplo de esto es la aplicación de Banco que realizamos este año, donde manipulando HTML y Javascript a través de DOM, probamos la acción directa de este código con la consola, dándonos errores en tiempo real y solucionándolos, quizá, en la misma.
## Consola del Back-end
La consola del back-end está en el servidor, donde se procesa la lógica de la aplicación y se manejan los datos. Esta interactúa con el servidor, gestiona aplicaciones, y ejecuta scripts de backend. Está enfocada en la infraestructura del servidor y el desarrollo de la lógica. El Backend es la infraestructura interna que hace que todo funcione de manera eficiente y segura.
En el ejemplo del Banco, la consola del Back, o sea el terminal, indica los errores de manera poco intuitiva, pero que dirigen al funcionamiento del programa, es decir al esqueleto que hace que todo funcione, no podemos probar en tiempo real.

