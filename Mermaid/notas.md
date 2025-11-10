# Diagramas de flujo con Mermaid

Una forma accesible de crear diagramas de flujo.

## Introducción

Mermaid es una forma accesible que tenemos para crear diagramas de flujo.

un diagrama de flujo es la representación gráfica de los pasos que debe seguir el algoritmo que vamos a diseñar para resolver un problema.

Gracias a esta tecnología nosotros escribiremos el código y luego quien vea podrá ver el gráfico al que está acostumbrado y sabrá cuál es el procedimiento que pensamos diseñar.

## Estructura básica

Podríamos dividir el diagrama en tres partes: el tipo de diagrama, el diseño de los pasos y la conexión entre los pasos.

### Tipo de diagrama

En la primera línea se pone el tipo de diagrama y, separado por un espacio, la orientación que tendrá.

Trabajaremos con el tipo flowchart. Los valores posibles para la orientación siempre van en mayúsculas y son:

- TD significa de arriba hacia abajo.
- BT significa de abajo hacia arriba.
- LR significa de izquierda a derecha.
- RL significa de derecha a izquierda.

### Diseño de los pasos

En las siguientes líneas, con un nivel de indentación, escribiremos los pasos que hay que seguir. Cada paso va en una línea.

El paso consta de un identificador y un texto encerrado entre símbolos.

El identificador sigue las mismas reglas que las variables en cualquier lenguaje de programación. Podemos usar nombres largos y significativos o podemos usar letras del abecedario que nosden un orden de lo que vamos haciendo.

El texto encerrado entre símbolos es lo que se verá el pantalla. Se dibujará el símbolo y dentro de él irá el texto que escribamos. Estos símbolos representan distintas cosas como datos, operaciones, condiciones, etcétera. En el último apartado encontrarás el listado con los símbolos que vayamos utilizando.

### Conexión entre pasos

Por último, y también con un nivel de indentación, debemos indicar cómo se conectan unos pasos con otros. En su versión más sencilla, pondremos el identificador de cada paso y una flecha que represente la unión con el identificador del siguiente paso. La flecha se escribe con dos guiones y el signo de mayor que.

## Programación secuencial

Son problemas que se resuelven empezando por la primera línea de código y terminando por la última. Es decir, no hay saltos, repeticiones ni tomas de decisiones.

### Ejemplo 1: Suma y producto

Recibir por teclado dos números enteros. Calcular la suma y el producto y mostrar ambos resultados.

Así se ve el diagrama:

```Mermaid
flowchart TD
    A([Inicio])
    B[/num1/]
    C[/num2/]
    D[suma = num1 + num2]
    E[producto = num1 * num2]
    F[/suma, producto/]
    G([Fin])

    A --> B --> C --> D --> E --> F --> G
```

## Listado de símbolos

- Paréntesis y corchetes. Significa inicio o fin.
- Corchetes y barras. Significa entrada o salida de datos.
- Corchetes. Significa operación.

[Volver al índice dle repositorio](../README.md)
