# Trabajo Práctico de Sintaxis y Semántica de los Lenguajes

## Enunciado
Desarrollar un scanner y parser para el lenguaje de programación Micro, cuya salida sea un lenguaje de bajo nivel.

Micro es un lenguaje muy simple que está diseñado, específicamente, para poseer un LP concreto sobre el que se pueda analizar la construcción de un
compilador básico.

### Definición informal

- El único tipo de dato es entero.
- Todos los identificadores son declarados implícitamente y con una
longitud máxima de 32 caracteres.
- Los identificadores deben comenzar con una letra y están compuestos
de letras y dígitos.
- Las constantes son secuencias de dígitos (números enteros).
- Hay dos tipos de sentencias:
Asignación
ID := Expresión;
Expresión es infija y se construye con identificadores,
constantes y los operadores +,–,* y /; los paréntesis están
permitidos.

- Entrada/Salidas : **leer** (lista de IDs), **escribir** (lista de Expresiones);
- Cada sentencia termina con un "punto y coma" (**;**). El cuerpo de un
programa está delimitado por **inicio** y **fin**.
