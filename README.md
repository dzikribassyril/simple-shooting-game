# Simple Shooting Game

A playable 2D shooter built in Unity and shipped as a ready-to-run Windows build (64-bit), with a bundled gameplay video demo.

![Unity](https://img.shields.io/badge/Unity-2022+-black)
![C#](https://img.shields.io/badge/C%23-blue)
![Windows](https://img.shields.io/badge/Platform-Windows-0078D6)
![License](https://img.shields.io/badge/License-MIT-green)

## Features

- Compiled Windows Player build — no Unity Editor or source project required to play
- Built on the Unity 2D Universal Render Pipeline with the new Input System
- Includes a full gameplay walkthrough video (`Video Demo.mp4`)

## Tech Stack

| Area | Technology |
|---|---|
| Engine | Unity (2D, Universal Render Pipeline) |
| Language | C# (compiled in player assemblies) |
| Input | Unity Input System |
| Platform | Windows x86_64 |

## Project Structure

```
.
├── Simple Shooting Game.exe          # Executable (double-click to play)
├── Simple Shooting Game_Data/        # Player assets, managed assemblies, resources
├── MonoBleedingEdge/                 # Bundled Mono runtime
├── D3D12/                            # D3D12 support files
├── UnityCrashHandler64.exe           # Unity crash handler
└── Video Demo.mp4                    # Gameplay walkthrough video
```

Note: this repository contains the compiled Unity *build*, not the Unity project source (scripts and scenes).

## Installation

```bash
git clone https://github.com/dzikribassyril/simple-shooting-game.git
cd simple-shooting-game
```

Requires Windows 10/11 (64-bit). No installation needed — the runtime is bundled with the build.

## Usage

```bash
./Simple\ Shooting\ Game.exe
```

Or double-click `Simple Shooting Game.exe` in File Explorer. Watch `Video Demo.mp4` for a gameplay preview and controls.

## License

[MIT](LICENSE) © 2026 Dzikri Basyril
