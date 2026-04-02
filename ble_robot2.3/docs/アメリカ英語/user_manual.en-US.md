# User Manual (Daily Operation)

This document is for operators who use the distributed app every day. It focuses on stability and repeatability rather than development workflow.

## Basic Operation Flow

1. Launch ble_robot_2.3.exe
2. Verify connection target as needed
3. Connect
4. Use manual control or automatic mode
5. Exit normally to save settings

## How Persistence Works

Values changed by user operation are saved to cf.rbcc. Internal managed values are saved to meta/*.rbci. About/License also reads from rbci, so text replacement is possible during operation.

## Notes When Changing Settings

- Create backups before manual editing
- Keep cf.rbcc and meta versions aligned for multi-device distribution
- Restart and verify reflection after changes

## Common Issues

For connection failures, check BLE address, robot state, and host Bluetooth state in order. If settings revert, verify write permission and security software quarantine behavior. If display text is not updated, confirm the target rbci was updated and reopen the screen.
