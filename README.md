# codigo-repaso-online-botones3-viejaescuela:

Este es un documento HTML que crea una página web con un campo de entrada y un botón.
Se espera que el usuario ingrese su nombre en el campo de entrada y haga clic en el botón "Aceptar".
Cuando se hace clic en el botón, el nombre ingresado se limpia y se capitaliza y luego se muestra en la página dentro de un div. 
La página web también tiene un oyente de eventos de keydown en el campo de entrada que desencadena el mismo comportamiento
cuando el usuario presiona la tecla "Enter".

El script utiliza JavaScript para agregar el oyente de eventos click al botón y el oyente de eventos keydown al campo de entrada.
El script también hace uso de window.onload

El bucle for es una estructura de control en JavaScript que permite repetir un bloque de código una cantidad determinada de veces. 
En este caso, el bucle for se utiliza para agregar un oyente de eventos click a cada uno de los botones con la clase "boton0". 
El código dentro del bucle for recorre cada uno de los elementos con la clase "boton0" en un arreglo y agrega un oyente de eventos click 
a cada uno de ellos. Además, el bucle también asigna un valor a la propiedad "input" de cada botón, dependiendo de su posición en el arreglo. 
Estos valores son los identificadores de los campos de entrada correspondientes a cada botón. De esta manera, cuando se hace clic en un botón, 
la función lista puede acceder al valor del campo de entrada correspondiente usando la propiedad "input" del botón que se hizo clic.
