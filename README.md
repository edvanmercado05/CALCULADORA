# EDVAN DANIEL MERCADO LAMAS 20490721
# ING SISTEMAS COMPUTACIONALES

# 2
document.querySelector(".display");: Esta línea de código selecciona el primer elemento en el documento HTML que tiene la clase CSS "display" y lo asigna a la variable display. En el contexto de la calculadora, esto probablemente se refiere al elemento que muestra los números y resultados de las operaciones.
# 3
const buttons = document.querySelectorAll("button");: Esta línea de código selecciona todos los elementos <button> en el documento HTML y los asigna a la variable buttons. querySelectorAll devuelve una NodeList que es similar a un array y contiene todos los elementos que coinciden con el selector CSS especificado.
# 4
buttonText = button.textContent;: Esta línea de código obtiene el texto contenido dentro del elemento <button> actual y lo asigna a la variable buttonText. En este contexto, button representa cada elemento <button> en el NodeList buttons obtenido anteriormente.
# 5
buttons.forEach((button) => { ...} ): Este código itera sobre cada elemento en el NodeList buttons y ejecuta la función de flecha proporcionada para cada elemento. En este caso, se utiliza para agregar un event listener de clic a cada botón.
# 6
button.addEventListener("click", () => { } ): Esta línea de código agrega un event listener de clic a cada botón. Cuando se hace clic en un botón, la función de flecha proporcionada se ejecuta. Dentro de esta función, generalmente se implementa la lógica para manejar la interacción del usuario, como actualizar la pantalla de la calculadora o realizar operaciones matemáticas.

# QUE SE REALIZO???

Calculadora Simple
Esta es una calculadora simple creada con HTML, CSS y JavaScript que puede realizar operaciones básicas como suma, resta, multiplicación y división. La calculadora tiene una interfaz intuitiva y funcionalidades básicas para realizar cálculos rápidos.

Contenido del Repositorio
El repositorio contiene los siguientes archivos:

index.html - El archivo HTML que contiene la estructura básica de la calculadora.
styles.css - El archivo CSS que contiene los estilos para la calculadora y sus botones.
script.js - El archivo JavaScript que contiene la lógica para las operaciones de la calculadora.
Uso
Para utilizar la calculadora, simplemente abre el archivo index.html en tu navegador. Puedes hacer clic en los botones numéricos y de operación para realizar cálculos. La pantalla mostrará el resultado de las operaciones y puedes borrar la pantalla o los dígitos individuales según sea necesario.

Funcionalidades
Suma, resta, multiplicación y división de números.
Borrar el último dígito.
Borrar toda la pantalla.
Mostrar "Error!" si la expresión es inválida.
