# Kotlin

## Variables
Sirve para almacenar datos temporales y utilizarlos a lo largo de nuestro código.. En kotlin las variables solo pueden almacenar un solo dato.
### TIPOS DE VARIABLES

VAR : Son variables de lectura y escritura, estas variables el valor puede cambiarse.

VAL : Son variables de solo lectura, dichas variables una vez asignado el valor no puede ser cambiado posteriormente.

CONST : es una variante de las variables de solo lectura, estas se definen fuera de la función y se escriben con la palabra reservada const seguida de la palabra reservada val, este tipo de variables son usada para valores que nunca cambian.

En Kotlin no se puede cambiar el tipo de dato con que se a definido una variable, si la variable se definio con el tipo de dato String solo podremos actualizar dicho valor por otro String, por ejemplo no podemos pasar de un string a un numero.


```kotlin
//Variable de lectura y escritura
var dinero = 10
println(dinero)
dinero = 5
println(dinero)

//variable de solo lectura (No se puede modificar)
val nombre = "Maria"
println(nombre)
    
//Las constantes no deben cambiar nunca y se generan antes de darle compilar la aplicación 
const val PI = 3.1416
println(PI)
```
## Tipos de datos

### Tipos de datos númericos:

Int: Para enteros de hasta 32bits.
```kotlin
val numeroDias: Int = 36526
```
Long: Para enteros de hasta 64bits.
```kotlin
val numeroCochesMundo: Long = 384400000L
```
Short: Para enteros de hasta 16bits.
```kotlin
val diasAno: Short = 3650
```
Byte: Para enteros de hasta 8bits.
```kotlin
var edad: Byte = 30
```
Float: Para decimales de hasta 32bits.
```kotlin
var peso: Float = 86.7F
```
Double: Para decimales de hasta 64bits.
```kotlin
var temperatura: Double = 12.23
```

### Tipos de datos Caracter

Es un tipo de dato representado po Char, estos tipos de datos no pueden ser tratados como números.
```kotlin
var letraDNI: Char = ‘D’
```
```kotlin
val letra:Char = '1'
if (letra == 1)  //Error por incompatibilidad de tipos
```
### Tipos de datos Booleanos
Representados por los tipos Boolean, y tienen valores marcados en verdader (true) y falso (false), se integran con los siguientes operadores para ser manipulados.
```kotlin
val esUnaVariable: Boolean = true
```
* || Disyunción.
* && Conjunción.
* ! Negación.

### Tipos de datos Cadenas.
Permite almacenar cadenas de caracteres.
```kotlin
var nombre: String = «Ivan»
```
### Arrays
Permite almacenar listas de objetos. 
```kotlin
val misColoresFavoritos = arrayOf(«naranja», «azul», «rojo», «negro»)
```
