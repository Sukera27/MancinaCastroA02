# Ejercicio 02

- Deberás de crear una clase en flutter que sea una plantilla de los botones, en la que le pases el argumento de texto y sustituirlo por los 3 botones que tenemos → 2 puntos
- Darle funcionalidad a los botones, cambios solo por consola → 2 puntos
- Cambios por pantalla → 4 puntos.
- README → 2 puntos.

## Descripción del Proyecto

El proyecto consiste en una aplicación Flutter que muestra un contador en pantalla. La interfaz incluye un título "CONTADOR", un número que representa el contador y tres botones: "+" para incrementar, "RESET" para reiniciar y "-" para decrementar el contador.

![ContadorFlutter](https://github.com/Sukera27/MancinaCastroA02/assets/122563964/07e12c1b-bdc5-463d-9711-60f2d349f5ff)     ![Counter2](https://github.com/Sukera27/MancinaCastroA02/assets/122563964/b6986db9-79a5-4fbc-93ab-dcc7d0a1f7cb)



## Estructura del Proyecto

# `main.dart`

Este archivo contiene la estructura principal de la aplicación Flutter. La clase `MyApp` es un `StatelessWidget` que inicializa y ejecuta el widget `Counter`.

## Widget `Counter`

- Este es un `StatefulWidget` que representa la pantalla del contador.
- Tiene una clase de estado, `CounterState`, que gestiona el estado del contador.
- El contador se puede incrementar, decrementar o reiniciar mediante los botones proporcionados.

### Botones (`ButtonCount`)

- Widget de botón personalizado definido en `btn_class.dart`.
- Acepta parámetros como texto, tamaño de fuente y una devolución de llamada `onPressed`.
- Se utiliza para los botones de incremento, decremento y reinicio en el widget `Counter`.

# `btn_class.dart`

Este archivo define el widget `ButtonCount`, que es un botón personalizado utilizado en la pantalla del contador. Es un `StatelessWidget` con texto personalizable, tamaño de fuente y una devolución de llamada `onPressed`.

## Requisitos Previos

- Tener Flutter y Dart instalados en tu entorno de desarrollo.

## Desarollador 
- Rafael Mancina Castro








