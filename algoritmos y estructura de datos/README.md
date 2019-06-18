# algoritmos y estructuras de datos
- algoritmos un algoritmo es una secuencia de pasos lógicos necesarios para llevar a cabo una tarea especifica, como la solución de un problema. Los algoritmos son independientes tanto del lenguaje de programación en que se expresan como de la computadora que los ejecuta.

- Diagrama de flujo (Representación gráfica) un diagrama de flujo  es una de las técnicas de representación de algoritmos Un diagrama de flujo es un diagrama que utiliza los símbolos (cajas) y que tiene los pasos del algoritmo escritos en esas cajas unidas por flechas, denominadas líneas de flujo, que indican la secuencia en que se deben ejecutar.

- TIPOS DE DATOS
El tipo de un dato es el conjunto de valores que puede tomar el programa durante la ejecución. Si se le intenta dar un valor fuera del conjunto se producirá un error. La asignación de tipos a los datos tiene dos objetivos principales: detectar errores en las operaciones, determinar cómo ejecutar estas operaciones

- Clasificaciones en los tipos de datos

- Dinámicos Este tipo te permite tener un mayor control sobre la gestión de memoria en tus programas. Con ellos puedes manejar el tamaño de tus variables en tiempo de ejecución.

- Estáticos Que un tipo de datos sea estático quiere decir que el tamaño que ocupa en memoria no puede variar durante la ejecución del programa.

- Tipos simples
Son los tipos básicos: entero, lógico, carácter y real. Y la mayoría de los lenguajes de programación los soportan, no como ocurre con los estructurados que pueden variar de un lenguaje a otro.
- Tipos estructurados
Los estructurados se refieren a colecciones de elementos. Las colecciones de elementos que aparecen al hablar de tipos estructurados son muy variadas: tenemos colecciones ordenadas que se representan mediante el tipo array, colecciones sin orden mediante el tipo conjunto, e incluso colecciones que contienen otros tipos, son los llamados registros. Arreglos, Conjuntos y Strings
- Tipos ordinales
Los ordinales son los más abundantes. Es ordinal porque el conjunto de valores que representa se puede contar, es decir, podemos establecer una relación uno a uno entre sus elementos y el conjunto de los números naturales. Pilas, Colas y Listas.
Dentro de los tipos simples ordinales, los más importantes son:
• El tipo entero .• El tipo lógico.• El tipo carácter.
- Tipos no-ordinales
Este tipo nos sirve para declarar variables que pueden tomar valores dentro del conjunto de los números reales. A diferencia de los tipos ordinales, los no-ordinales no se pueden contar. No se puede establecer una relación uno a uno

- Arreglos Unidimensionales
Un arreglo unidimensional es un tipo de datos estructurado que está formado de una colección finita y ordenada de datos del mismo tipo.
El tipo de acceso a los arreglos unidimensionales es el acceso directo, es decir, podemos acceder a cualquier elemento del arreglo sin tener que consultar avelementos anteriores o posteriores, esto mediante el uso de un índice.
Para implementar arreglos unidimensionales se debe reservar espacio encmemoria, y se debe proporcionar la dirección base del arreglo, la cota superior y la inferior.
- Arreglos Bidimensionales
Este tipo de arreglos al igual que los anteriores es un tipo de dato estructurado,finito ordenado y homogéneo. El acceso a ellos también es en forma directa por medio de un par de índices.
Los arreglos bidimensionales se usan para representar datos que pueden verse como una tabla con filas y columnas. La primera dimensión del arreglo representa las columnas, cada elemento contiene un valor y cada dimensión representa una relación
- cadenas
La cadena es una secuencia de caracteres que se interpretan como un dato único. Su longitud puede ser fija o variable por lo que, además de saber que están constituidas por caracteres alfanuméricos, hemos de conocer su longitud.
En una variable tipo cadena se puede almacenar una palabra, una frase, una matricula de coche, una temperatura, etc.

Sobre datos de tipo cadena se pueden realizar las siguientes operaciones:

Asignación: Guardar una cadena en una variable tipo cadena. Como en toda asignación a una variable, la cadena que se guarda puede ser una constante, una variable tipo cadena o una expresión que produzca un dato tipo cadena. Por
ejemplo:
nombre ← “Pepe”

nombre ← mi-nombre-de-pila

Concatenación: Formar una cadena a partir de dos ya existentes, yuxtaponiendo los caracteres de ambas. Si se denota por // al operador “concatenación”, el resultado de:

“ab” // “cd” es “abcd”

Nótese que las constantes de tipo cadena se escriben entre comillas, para no confundirlos con nombres de variables u otros identificadores del programa.

Extracción de subcadena: Permite formar una cadena (subcadena) a partir de otra ya existente. La subcadena se forma tomando un tramo consecutivo de la cadena inicial. Si NOMBRE es una variable de tipo cadena que contiene “JUAN PEDRO
ORTEGA” y denotamos por (n:m) la extracción de m caracteres tomados a partir del lugar n, entonces NOMBRE(6:5) es una subcadena que contiene “PEDRO”.

Un caso particular de extracción que se utiliza a menudo es el de extraer un único caracter. Por ello se suele proporcionar un método directo: el nombre seguido por
el lugar que ocupa dentro de la cadena. Así, en el ejemplo anterior, NOMBRE(6) = “P” = NOMBRE(6:1)

Obtención de longitud: La longitud de una cadena es un dato de tipo entero, cuyo valor es el número de caracteres que contiene ésta. En el primero de los dos métodos anteriores de representación de cadenas, la longitud se obtiene
consultando el número de la primera casilla; en el segundo método la longitud es el número de orden que ocupa el caracter de fin-de-cadena, menos uno.

Comparación de cadenas: Consiste en comparar las cadenas carácter a carácter comenzando por el primero de la izquierda, igual que se consulta un diccionario. El orden de comparación viene dado por el código de E/S del ordenador (ASCII habitualmente). Así la expresión booleana: “Jose” < “Julio”, se evaluara como verdadera. Nótese que en los códigos de E/S, las mayúsculas y las minúsculas son
diferentes, dando lugar a resultados paradójicos en la comparación, así pues, si el código de E/S es ASCII, donde las mayúsculas tienen códigos inferiores a las minúsculas, se cumpliría que “Z” < “a”. 
