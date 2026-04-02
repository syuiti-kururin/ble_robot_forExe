# Mastery Manual (Operations and Maintenance)

## Key Points of cf.rbcc

- last write time is checked against OS file update time.
- With user!! flag:
  - Example: $`last write time yyyy/mm/dd hh:mm:ss.xx user!!`$
  - Indicates manual edit.
  - Large timestamp mismatches show warnings but loading continues.
  - user!! is removed on differential write.

## Differential Update

- Only changed keys are updated.
- last write time is updated if at least one key changed.
- Broken format or version mismatch triggers full reformat.

## License

- See LICENSE.md.
