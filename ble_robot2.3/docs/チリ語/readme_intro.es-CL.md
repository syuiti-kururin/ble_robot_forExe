# README (Introducción)

ROBO BLE Controller 2.3 es una aplicación de control para Windows orientada al aprendizaje y demostraciones de ROBO-ONE Beginner. Controla el robot por BLE, visualiza datos recibidos, guarda configuraciones y permite operación repetible en clases.

Este paquete separa la configuración editable por el usuario de la configuración interna gestionada por operación. Así se pueden ajustar valores después de distribuir, sin recompilar el ejecutable.

## Estructura pública actual

- Ejecutable: ble_robot_2.3.exe
- Configuración de usuario: cf.rbcc
- Configuración interna: meta/*.rbci
- Datos de logotipo: meta/*.rbcl
- Documentación: docs/

## Motivo de la separación

cf.rbcc guarda parámetros de uso diario. meta/*.rbci guarda valores internos que pueden requerir ajustes posteriores. Separar estos datos evita fijar valores mutables dentro del exe y mejora mantenibilidad y protección de datos.
