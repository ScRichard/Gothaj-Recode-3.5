# Gothaj Recode 3.5 — Source Code

## Features

### Event Bus
Custom event bus used to subscribe and react to Minecraft/client events.

### UI
Modern UI for modules, settings, and client UX.

### Commands
Command system for toggling features, managing binds, and changing settings.

### Client Settings
Client settings for visual effects such as blur and bloom.

### Modules
Modules are split into categories:
- COMBAT
- MOVEMENT
- PLAYER
- VISUALS
- CLIENT

### Binds
Modules can be bound to both **keyboard** and **mouse**.

### Scripts (WIP)
JavaScript-based scripting for modules.

### Utilities
Shared client utilities, including:
- animations (easings)
- buttons/components
- config & file saving system
- font system
- inventory / math / noise helpers
- movement, notifications
- rendering utilities, resources, rotation
- scissors/clipping, shaders
- targeting, UI helpers

### Value System (parent-based)
Typed settings/value system:
- Boolean
- Category
- Color
- Description
- Location
- Mode
- Multiple Boolean
- Number
- Range

---

## Setup (MCP 1.8.8)

### Prerequisites
- Minecraft **1.8.8** installed and launched at least once
- **MCP 1.8.8** (Mod Coder Pack)
- IDE: IntelliJ IDEA / Eclipse / VS Code (recommended: IntelliJ)

### Step 1 — Download MCP 1.8.8
1. Download **Mod Coder Pack (MCP) 1.8.8** from https://www.modcoderpack.com
2. Extract `MCP.zip` into a new folder.

### Step 2 — Prepare Minecraft
1. Open Minecraft Launcher
2. Run **Minecraft 1.8.8** once, then close it.

### Step 3 — Decompile with MCP
1. Open the extracted MCP folder
2. Run `decompile.bat`

### Step 4 — Add Gothaj Client source
1. Open the MCP folder in your IDE
2. Delete the files inside the `./src` folder (keep the folder)
3. Clone this repository into `./src`:

```bash
git clone https://github.com/ScRichard/GOTHAJ_RECODE_UNRELEASED.git src
