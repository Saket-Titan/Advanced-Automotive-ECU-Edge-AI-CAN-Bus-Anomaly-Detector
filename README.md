# Automotive Firmware Mono-repo

## Environment setup
- Toolchain: Zephyr SDK/ARM toolchain installed.
- Tools: west, cmake, ninja, python3.

## West commands used
- west init -m <your-manifest-or-zephyr-url> [--mr <tag/branch>]
- west update
- west build -b <board> <app_path>

## Board target(s) and console
- Primary: stm32g431rb
- Console: ST-LINK VCP at 115200 8N1 (Virtual COM Port)[6].
