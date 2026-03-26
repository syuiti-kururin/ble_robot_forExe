# Manual de Maestría (Operación)

## cf.rbcc
- Se valida `last write time` con mtime del archivo.
- `user!!` indica edición manual.
- Si está fuera de rango: advertencia, pero se carga.
- En sincronización se elimina `user!!`.

## Política de actualización
- Solo claves cambiadas.
- Si hay cambio, se actualiza `last write time`.
- Formato roto o versión distinta: reescritura normalizada.

Licencia: `LICENSE.md`.
