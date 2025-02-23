# MCBE ScriptAPI Template

## Overview

This project is a template for developing Minecraft Bedrock Edition ScriptAPI projects using TypeScript. It compiles your TypeScript code into JavaScript and then automatically copies then into your minecraft world.

## Configuration

Before running the compile script, configure the following constants in `config.json`:

```json
{
    "dest": "(MINECRAFT WORLD LOCATION)",
    "pack_name": "(PACK NAME)"
}
```

## Using

```
npm run compile
```