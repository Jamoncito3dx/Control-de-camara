# Unity Mouse Camera Controller

Este proyecto incluye un script para controlar la cámara en Unity usando el movimiento del mouse. El script permite que la cámara siga la vista del jugador, proporcionando una rotación suave en primera o tercera persona.

## Características

- **Rotación horizontal**: El movimiento del mouse en el eje X rota al personaje.
- **Rotación vertical**: El movimiento del mouse en el eje Y inclina la cámara hacia arriba y abajo, con límites para evitar rotaciones extremas.
- **Bloqueo del cursor**: El cursor se bloquea en el centro de la pantalla para una experiencia inmersiva.
- **Sensibilidad del mouse**: La sensibilidad del mouse es configurable desde el inspector de Unity.

## Requisitos

- Unity 2020.3 o superior.
- Un **GameObject** (por ejemplo, un jugador) que tenga el componente **CharacterController** para el control del movimiento.
- Una **Cámara** que siga al jugador y sea controlada por este script.

## Instalación y Configuración

### 1. CameraController Script

1. Crea un nuevo script llamado `CameraController`.
2. Asigna este script al objeto de la Cámara.
En el inspector de Unity:
Asigna el objeto del jugador (que tiene el CharacterController) al campo playerBody.
Ajusta la sensibilidad del mouse (mouseSensitivity) según sea necesario.
El cursor estará bloqueado al iniciar el juego para que el jugador pueda moverse libremente sin que el mouse salga de la ventana de juego.
