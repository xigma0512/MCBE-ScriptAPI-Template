# MCBE ScriptAPI Template

## Overview

This project is a template for developing Minecraft Bedrock Edition ScriptAPI projects using TypeScript. It compiles your TypeScript code into JavaScript and then automatically copies the resulting Behavior Pack files into your designated Minecraft world Behavior Pack folder.

## Configuration

Before running the compile script, configure the following constants in `config.json`:

```json
{
    "destination": "(MINECRAFT WORLD BEHAVIOR PACK LOCATION)",
    "pack_name": "(PACK NAME)"
}
```

## Using

```
npm run compile
```