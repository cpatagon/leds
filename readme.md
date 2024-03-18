# Trabajo Práctico 2: TDD para Controlador de LEDs

## Especialización en Sistemas de Software Embebido - Curso de Embebidos Testing

### Descripción

Este repositorio contiene el trabajo práctico 2 (TP2), centrado en el desarrollo de un controlador de LEDs utilizando la técnica de Desarrollo Guiado por Pruebas (TDD, por sus siglas en inglés). El objetivo es completar el trabajo presentado en clase, implementando un conjunto de pruebas unitarias que guíen el desarrollo del software de manera iterativa y enfocada en la funcionalidad.

### Pruebas Implementadas

Las pruebas desarrolladas para el controlador de LEDs son:

- **Test de Inicialización**: Verifica que después de la inicialización, todos los LEDs queden apagados.
- **Prender un LED Individual**: Comprueba la capacidad de encender un LED específico.
- **Apagar un LED Individual**: Verifica la capacidad de apagar un LED específico.
- **Manejo de Múltiples LEDs**: Pruebas para encender y apagar múltiples LEDs.
- **Prender Todos los LEDs**: Verifica que se puedan encender todos los LEDs simultáneamente.
- **Apagar Todos los LEDs**: Comprueba que se puedan apagar todos los LEDs de una vez.
- **Consulta del Estado de un LED**: Permite consultar el estado actual (encendido/apagado) de un LED específico.

### Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

/TP2
│
├── src/ - Código fuente del controlador de LEDs.
│ ├── leds.c
│ └── leds.h
│
├── test/ - Pruebas unitarias.
│ └── test_leds.c
│
└── README.md - Este archivo.
