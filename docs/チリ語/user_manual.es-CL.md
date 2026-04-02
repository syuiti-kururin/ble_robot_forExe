# Manual de Usuario (Operación Diaria)

Este documento está dirigido a operadores que usan la app distribuida en práctica diaria. Prioriza estabilidad y repetibilidad por encima del flujo de desarrollo.

## Flujo básico

1. Abrir ble_robot_2.3.exe
2. Verificar destino de conexión si corresponde
3. Conectar
4. Operar en modo manual o automático
5. Salir normalmente para guardar ajustes

## Persistencia

Los cambios del usuario se guardan en cf.rbcc. Los valores internos se guardan en meta/*.rbci. About/License también se lee desde rbci, por lo que se puede cambiar texto en operación.

## Precauciones al cambiar

- Crear respaldo antes de editar manualmente
- Alinear versión de cf.rbcc y meta en distribución multi-equipo
- Reiniciar y verificar reflejo después de cambios

## Problemas comunes

Si falla la conexión, revisar dirección BLE, estado del robot y Bluetooth del host en ese orden. Si se pierden ajustes, revisar permisos de escritura y cuarentena de seguridad. Si texto no cambia, confirmar actualización del rbci y reabrir la pantalla.
