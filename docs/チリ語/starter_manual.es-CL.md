# Manual Inicial (Primera Configuración)

Este documento es para principiantes o responsables de primera puesta en marcha que necesitan llegar rápido a una conexión funcional. Está pensado para uso con paquete distribuido y no requiere experiencia de desarrollo Python.

## 1. Preparación

- PC con Windows
- Robot con BLE disponible
- Paquete distribuido (exe, cf.rbcc, meta, tools, docs)

## 2. Instalación de Thonny (si se valida el lado robot)

Use Thonny cuando en la clase se requiera cargar o revisar programas del robot.

1. Instalar Thonny
2. Ajustar el intérprete según el entorno indicado en clase
3. Confirmar parámetros de conexión del robot
4. Ejecutar una prueba mínima de envío/recepción antes de pasar a la app de PC

Thonny no es obligatorio para todos, pero sirve para aislar fallas del lado robot.

## 3. Primer inicio de la app PC

1. Ejecutar ble_robot_2.3.exe
2. Abrir ajustes y configurar dirección BLE
3. Presionar Connect
4. Verificar respuesta con cruceta o gamepad

## 4. Comprender archivos de configuración

- cf.rbcc: configuración de usuario (destino, teclas, UI)

Con esta separación, los cambios posteriores se absorben del lado rbci y no hace falta editar el ejecutable.
