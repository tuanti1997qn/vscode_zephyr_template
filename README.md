# Template zephyr project for working with visual studio code

This is a template vscode project for zephyr. Support freestanding application.

Inspired by [zephyr-vscode-example](https://github.com/beriberikix/zephyr-vscode-example/tree/main).

## Usage

Support build, flash and debug.

For debugging:

- Modify device field in [.vscode/launch.json](.vscode/launch.json) to your device use with jlink. For more configuration or setup for other debugger, checkout [cortex debug wiki](https://github.com/Marus/cortex-debug/wiki/J-Link-Specific-Configuration).
- Modify path to your prefer gdb. My suggest is keep gdb-multiarch or zephyr sdk gdb

For ntelliSense:

- Modify zephyr sdk path in [.vscode/settings.json](.vscode/settings.json)

For build and flash

- Modify build args in [.vscode/tasks.json](.vscode/tasks.json) to build your board.

F5 and enjoy debugging, hope so :yum:.
