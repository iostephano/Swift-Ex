# The Basic

# [Constantes y Variables]

1. Declara una constante llamada `pi` y asígnale el valor 3.14159
2. Declara una variable llamada `edad` con el valor 25, luego actualízala a 26.
3. Declara una constante `nombre` y asígnale tu nombre.
4. Crea una variable `numeroAleatorio` e inicialízala con cualquier número entero, luego multiplícala por 2 y almacena el resultado en la misma variable.
5. Declara dos constantes: `base` y `altura`. Luego calcula el área de un triángulo.
6. Declara una variable `mensaje` sin inicializarla. Asigna el valor `"Hola, mundo"` y luego imprímela.
7. Usa `type annotation` para declarar una constante llamada `precio` de tipo `Double` y asígnale 19.99.
8. Declara una constante `esMayorDeEdad` con un valor `true`.
9. Declara una variable `saludo` con el valor `"Hola"`. Luego concaténala con otra variable llamada `nombre`.
10. Declara una variable `calificacion` y asígnale el valor 80. Suma 5 y resta 3, luego almacena el resultado en la misma variable.
11. Declara una constante `minutosEnHora` y asígnale el valor 60. Luego calcula cuántos minutos hay en 5 horas.
12. Declara dos constantes, `x` y `y`, y asígnales los valores 10 y 15, respectivamente. Calcula su promedio.
13. Declara una variable `saldo` e inicialízala con 1000. Luego réstale 200.
14. Declara una constante `velocidadLuz` con el valor 299792458 (en m/s).
15. Declara una variable `ciudad` sin inicializar. Asigna el valor `"Hobart"` más tarde.
16. Declara una constante `esFestivo` con el valor `false`.
17. Declara una variable `cantidadProductos` y asígnale el valor 10. Luego multiplícalo por 3.
18. Usa interpolación para declarar una constante `mensajeFinal` que combine el valor de dos constantes: `usuario` y `puntaje`.
19. Declara una variable `temperatura` con el valor 20 y cámbiala a 15 después.
20. Declara una constante `piRedondeado` que almacene el valor de `pi` redondeado a 2 decimales.
- ***Soluciones***
    
    ```swift
    // 1
    let pi = 3.14159
    
    // 2
    var edad = 25
    edad = 26
    
    // 3
    let nombre = "Tu Nombre"
    
    // 4
    var numeroAleatorio = 7
    numeroAleatorio *= 2
    
    // 5
    let base = 5.0
    let altura = 10.0
    let areaTriangulo = (base * altura) / 2
    
    // 6
    var mensaje: String
    mensaje = "Hola, mundo"
    print(mensaje)
    
    // 7
    let precio: Double = 19.99
    
    // 8
    let esMayorDeEdad = true
    
    // 9
    var saludo = "Hola"
    var nombreUsuario = "Mundo"
    saludo += " " + nombreUsuario // Hola Mundo
    
    // 10
    var calificacion = 80
    calificacion += 5
    calificacion -= 3
    
    // 11
    let minutosEnHora = 60
    let minutosEnCincoHoras = minutosEnHora * 5
    
    // 12
    let x = 10.0
    let y = 15.0
    let promedio = (x + y) / 2
    
    // 13
    var saldo = 1000
    saldo -= 200
    
    // 14
    let velocidadLuz = 299_792_458 // m/s
    
    // 15
    var ciudad: String
    ciudad = "Hobart"
    
    // 16
    let esFestivo = false
    
    // 17
    var cantidadProductos = 10
    cantidadProductos *= 3
    
    // 18
    let usuario = "Juan"
    let puntaje = 95
    let mensajeFinal = "Usuario: \(usuario), Puntaje: \(puntaje)"
    
    // 19
    var temperatura = 20
    temperatura = 15
    
    // 20
    let piRedondeado = Double(round(100 * pi) / 100)
    ```
