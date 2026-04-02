# README (Introduction)

ROBO BLE Controller 2.3 is a Windows control app for ROBO-ONE Beginner learning and demonstration use. It controls the robot over BLE, visualizes incoming data, stores settings, and supports repeatable operation in classroom environments.

This package separates user-edited settings from internally managed settings. This lets you safely change operational values after distribution without rebuilding the executable itself.

## Current Public Structure

- Executable: ble_robot_2.3.exe
- User settings: cf.rbcc
- Internal settings: meta/*.rbci
- Logo-related data: meta/*.rbcl
- Documentation: docs/

## Why Settings Are Separated

cf.rbcc stores day-to-day operator settings. meta/*.rbci stores internal values that may require post-release adjustment. Keeping internal data outside the executable improves maintainability and data protection.

## Recommended Reading Order

1. starter_manual.en.md: first setup and first connection
2. user_manual.en.md: daily operation
3. edu_manual.en.md: classroom operation
4. ad_manual.en.md: distribution and management policy
5. mastery_manual.en.md: maintenance and validation
