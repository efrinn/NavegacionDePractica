# PracticaNavegacion
# Buzón UAM

## Descripción

Buzón UAM es una aplicación móvil básica desarrollada en Android Studio utilizando Kotlin y Jetpack Compose.

La aplicación permite al usuario navegar entre tres pantallas principales: Inicio, Queja o Reclamo y Sugerencia. Su propósito es simular un pequeño buzón digital donde el usuario puede elegir si desea realizar un reclamo o enviar una sugerencia.

Este proyecto fue realizado como práctica de navegación entre pantallas en aplicaciones móviles.

## Objetivo

Implementar un sistema de navegación funcional entre pantallas utilizando Jetpack Compose, comprendiendo el flujo de navegación y el manejo de múltiples vistas dentro de una aplicación Android.

## Pantallas de la aplicación

### Pantalla 1: Inicio

La pantalla principal muestra el nombre de la aplicación y dos botones principales:

- Queja o Reclamo
- Sugerencia

Cada botón permite navegar hacia la pantalla correspondiente.

### Pantalla 2: Queja o Reclamo

Esta pantalla permite al usuario escribir una queja o reclamo.

Incluye:

- Título de la pantalla
- Campo de texto para escribir el reclamo
- Botón para enviar el reclamo
- Botón para volver al inicio
- Botón para ir a sugerencias

### Pantalla 3: Sugerencia

Esta pantalla permite al usuario escribir una sugerencia.

Incluye:

- Título de la pantalla
- Campo de texto para escribir la sugerencia
- Botón para enviar la sugerencia
- Botón para volver al inicio
- Botón para ir a quejas o reclamos

## Tecnologías utilizadas

- Kotlin
- Android Studio
- Jetpack Compose
- Navigation Compose

## Flujo de navegación

```text
Inicio
 ├── Queja o Reclamo
 │    ├── Volver al Inicio
 │    └── Ir a Sugerencia
 │
 └── Sugerencia
      ├── Volver al Inicio
      └── Ir a Queja o Reclamo
