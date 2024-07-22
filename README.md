# Definicion de Variables

En Kotlin, las variables se definen utilizando la palabra clave val para valores inmutables (constantes) y var para variables mutables.
Ej:
- val nombre: String = "Juan"
- var edad: Int = 30

# Manejo de nulos
Kotlin maneja el manejo de nulos de manera segura, lo que ayuda a prevenir errores de referencia nula (NullPointerException). Para permitir que una variable acepte valores nulos, se usa el operador ? después del tipo de dato:
- var apellido: String? = null

# Parametros opcionales en funciones
En Kotlin, puedes definir parámetros opcionales en funciones usando valores por defecto:
- fun saludar(nombre: String, saludo: String = "Hola") {
    println("$saludo, $nombre!")
}

- saludar("Ana") // Imprime: Hola, Ana!
- saludar("Carlos", "¡Buen día") // Imprime: ¡Buen día, Carlos!

# Comentarios
Los comentarios en Kotlin se pueden hacer de varias maneras:
- // Este es un comentario de una línea
- /*
 * Este es un comentario
 * de bloque en Kotlin
 */
