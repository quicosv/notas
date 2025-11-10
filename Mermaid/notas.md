\# Diagramas de flujo con Mermaid



Una forma accesible de crear diagramas de flujo.



\## Introducción



Mermaid es una forma accesible que tenemos para crear diagramas de flujo.



Un diagrama de flujo es la reperesentación gráfica de los pasos que vamos a dar para solucionar un problema.



Gracias a esta tecnología nosotros escribiremos el código en texto y luego se visulizará el gráfico para que quien vea sepa cuál es el proceso que estamos pensando para nuestro algoritmo.



\## Estructura básica



En la primera línea indicaremos el tipo de diagrama y, separado por un espacio, la orientación que tendrá. Trabajaremos con el tipo flowchart y sus posibles orientaciones son:



* TD significa de arriba hacia abajo.
* \- BT significa de abajo hacia arriba.
* \- LR significa de izquierd aa derecha.
* \- RL significa de derecha a izquierda.

Las letras de cualquiera de estas orientaciones están en mayúsculas.



En las slguientes líneas, con un nivel de indentación, estructuramos los pasos a seguir. Escribiremos un paso por cada línea. Cada paso consta de:



* Un identificador.
* \- Un texto encerrado entre diversos símbolos.

Entre el nombre del identificador y el texto con símbolos no hay espacios.



El nombre del identificador sigue las reglas que suelen seguir los nombres de variables en los lenguajes de programación, aunque hay quien utiliza las letras en orden alfabético para tener una sensación de orden.



En cuanto al texto con símbolos, el texto es lo que se verá en pantalla y los símbolos hacen referencia al dibujo que tendrá ese paso en el diagrama de flujo. El símbolo dependerá de lo que queremos representar. Al final está el listado de símbolos.



La última línea del diagrama contiene el orden en el que se ejecutarán los pasos que hemos descrito. Lo estableceremos escribiendo los identificadores en el orden en el que deben ir y los uniremos con flechas. Las flechas se escriben usando dos guiones y el signo de mayor que.



A partir de aquí iremos poniendo ejemplos de los distintos tipos de programación.



\## Programación secuencial



Son problemas que se resuelven empezando por la primera línea del código y terminando por la última. Es decir, no hay ningún tipo de repetición ni toma de decisiones.



\## Listado de símbolos



* Paréntesis y corchetes. Significa inicio o fin.
* \- Corchetes y barras. Significa entrada o salida de datos.
* \- Corchetes. Significa operación.
