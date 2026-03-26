# Mastery Manual (Operations)

## cf.rbcc
- `last write time` is validated against file mtime.
- `user!!` means manual user edit.
- Out-of-range `user!!` time causes warning (load continues).
- `user!!` is removed during sync write.

## Update policy
- Changed keys only.
- Any change updates `last write time`.
- Broken format/version mismatch triggers normalized full rewrite.

License: `LICENSE.md`.
