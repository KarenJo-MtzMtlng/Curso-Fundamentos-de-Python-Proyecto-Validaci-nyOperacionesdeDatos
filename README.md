Este repositorio está conformado por dos programas en Python que realizan las siguientes funciones:

-Calculadora de Longitud de Palabras: Este programa mide la longitud de una palabra ingresada por el usuario. Si la palabra tiene entre 4 y 8 letras, se considera válida. De lo contrario, el programa indica cuántas letras faltan o sobran y solicita una nueva palabra hasta que se ingrese una válida.

-Identificadora de Cuadrante: Este programa determina en cuál de los cuatro cuadrantes del plano cartesiano se encuentra un punto dado por el usuario, en función de las coordenadas X e Y ingresadas.

Al iniciar la Calculadora de Longitud de Palabras, se muestra un mensaje de bienvenida. Luego, el usuario ingresa una palabra, y el programa calcula su longitud. Dependiendo del resultado:
Si la palabra tiene entre 4 y 8 letras, se considera correcta y se muestra un mensaje de éxito. 
Si la palabra tiene menos de 4 letras, se indica cuántas letras faltan. 
Si la palabra tiene más de 8 letras, se indica cuántas letras sobran.

En la identificadora de Cuadrante, se solicita al usuario que ingrese las coordenadas X e Y de un punto en el plano cartesiano. Si cualquiera de los valores es 0, el programa pedirá un valor diferente, ya que el origen no pertenece a ningún cuadrante. Una vez ingresadas coordenadas válidas, el programa determina y muestra el cuadrante en el que se encuentra el punto, junto con un gráfico sencillo que representa el plano.

El programa utiliza colores en la terminal para mejorar la experiencia del usuario: Verde para mensajes de bienvenida. Cian para indicar el cuadrante en el que se encuentra el punto y para indicar la longitud de la palabra. Amarillo para mensajes de despedida.
