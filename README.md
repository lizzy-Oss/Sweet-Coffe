# Sweet Brew ☕

Sweet Brew es una aplicación móvil desarrollada con **Flutter** que recrea la experiencia de una cafetería digital moderna, enfocada en una navegación intuitiva, diseño visual limpio y una interacción agradable para el usuario.

El proyecto fue construido con una estructura modular basada en pantallas independientes y componentes reutilizables, permitiendo escalabilidad, mantenimiento sencillo y futuras integraciones con servicios externos como bases de datos, autenticación persistente o sistemas de pago.

La aplicación combina una estética cálida inspirada en cafeterías contemporáneas con funcionalidades prácticas de exploración de productos, detalle de bebidas, gestión de carrito, registro de usuarios y autenticación biométrica.

---

# Objetivo del proyecto

El objetivo principal de Sweet Brew es desarrollar una aplicación móvil que permita practicar y aplicar conceptos fundamentales del desarrollo con Flutter, tales como:

- diseño de interfaces modernas
- navegación entre pantallas
- manejo de assets
- integración de plugins nativos
- captura de imágenes
- autenticación biométrica
- organización modular del código
- buenas prácticas de estructura de proyecto

Además, el proyecto está pensado como una base sólida para evolucionar hacia una aplicación real de comercio móvil.

---

# Características principales

## Autenticación de usuario

La aplicación incluye una pantalla de acceso que permite:

- ingreso de correo electrónico
- ingreso de contraseña
- navegación hacia registro de cuenta
- acceso a la pantalla principal

El flujo fue diseñado para ser simple, rápido y visualmente consistente con el resto de la aplicación.

---

## Registro de cuenta

El módulo de registro incorpora:

- nombre completo
- correo electrónico
- contraseña
- selección de fotografía de perfil
- carga de imagen desde galería o archivos
- captura de fotografía usando cámara
- activación de acceso biométrico mediante huella digital

Este módulo utiliza plugins nativos para aprovechar funcionalidades del dispositivo.

---

## Exploración de productos

La pantalla principal permite:

- visualizar promociones
- consultar cafés destacados
- navegar entre productos
- acceder a detalles individuales
- explorar especiales del día

La interfaz está diseñada para priorizar legibilidad, espacio visual y navegación natural.

---

## Detalle del producto

Cada bebida incluye:

- imagen del producto
- nombre
- precio
- descripción
- selección de tamaño
- toppings
- botón de agregado al carrito

Esto proporciona una experiencia similar a aplicaciones comerciales reales.

---

## Carrito de compra

El módulo de carrito permite:

- visualizar productos agregados
- aplicar código promocional
- calcular subtotal
- calcular descuento
- calcular total final
- continuar al proceso de entrega

---

## Perfil de usuario

La sección de perfil incluye:

- avatar
- datos visuales
- historial
- preferencias
- acceso a ubicación
- navegación hacia mapa

---

# Tecnologías utilizadas

## Framework principal

- **Flutter**

## Lenguaje

- **Dart**

## Librerías y paquetes

- **google_fonts**
- **image_picker**
- **local_auth**

---

# Arquitectura del proyecto

La aplicación está organizada mediante pantallas independientes que encapsulan responsabilidades específicas.

## Estructura principal

```text
lib/
├── main.dart
├── login_page.dart
├── register_page.dart
├── home_page.dart
├── coffee_detail_page.dart
├── cart_page.dart
├── profile_page.dart
├── delivery_page.dart
└── location_page.dart
## Autor

Lizbeth Ramirez Cruz

Proyecto académico orientado a práctica de desarrollo móvil con Flutter.

##Licencia

Proyecto de uso educativo, demostrativo y de aprendizaje.
