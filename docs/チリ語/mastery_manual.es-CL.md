# Manual de Maestría (Operación y Mantenimiento)

## Puntos clave de cf.rbcc

- last write time se valida con marca de tiempo del sistema.
- Con flag user!!:
  - Ejemplo: $`last write time yyyy/mm/dd hh:mm:ss.xx user!!`$
  - Indica edición manual.
  - Diferencias grandes muestran advertencia, pero la carga continúa.
  - user!! se elimina al guardar por diferencia.

## Actualización diferencial

- Se actualizan solo claves cambiadas.
- Se actualiza last write time si hubo al menos un cambio.
- Formato roto o versión no coincidente provoca reformateo total.

## Licencia

- Ver LICENSE.md.
