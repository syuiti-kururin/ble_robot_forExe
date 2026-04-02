# Admin Manual (Public Operations Scope)

This document is for managers responsible for distribution, publication, and operational governance. It only describes what is safe to disclose publicly.

## Responsibility Separation in Public Build

- cf.rbcc: source of truth for user settings
- meta/*.rbci: internal operational data
- meta/*.rbcl: logo and related data

The purpose of this separation is safe post-release maintenance and avoiding any assumption that executable internals should be edited directly.

## Recommended Distribution Layout

- ble_robot_2.3.exe
- cf.rbcc
- meta/
- tools/
- docs/

tools is used for internal settings maintenance. It may be optional for end-users but is recommended for operations staff.

## Change Management Policy

- User experience settings belong in cf.rbcc
- Operational/internal specification settings belong in rbci
- Keep release-level change history and recovery backups

## Publication Checklist

1. Launch and connect
2. Settings persistence
3. rbci change reflection
4. tools launch
5. Documentation consistency
