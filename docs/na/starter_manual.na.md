# Starter Manual (First Setup)

This document is for beginners or first-time setup operators who need to reach a successful connection quickly. It assumes distribution package operation and does not require Python development experience.

## 1. Preparation

- Windows PC
- Robot hardware with BLE communication support
- Distribution set (exe, cf.rbcc, meta, tools, docs)

## 2. Thonny Setup (When Robot-Side Check Is Needed)

Use Thonny in classes where writing or checking robot-side programs is required.

1. Install Thonny
2. Set the interpreter to the environment specified in class
3. Confirm robot-side connection settings
4. Run a minimal send/receive test before moving to the PC app

Thonny is not mandatory for all users, but it is effective for isolating robot-side issues.

## 3. First Launch of PC App

1. Start ble_robot_2.3.exe
2. Open settings and set the BLE address
3. Press Connect
4. Verify response with D-pad or gamepad

## 4. Understanding Configuration Files

- cf.rbcc: user settings (target device, control keys, UI)

With this separation, post-release changes can be handled on the rbci side and executable re-editing is unnecessary.

## 5. Initial Troubleshooting

If connection fails, check BLE address, robot power, and waiting state in order. If settings do not apply, confirm that cf.rbcc and meta exist in the execution folder and that write permissions are available.
