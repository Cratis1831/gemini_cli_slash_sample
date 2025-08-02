# Gemini CLI Slash Commands Sample

Custom slash commands for the Gemini CLI.

## Commands

### `/ios-icons`

Generates all required iOS app icon sizes from a single 1024x1024 PNG file.

**Usage:**
```
/ios-icons path/to/icon-1024.png
```

**Requirements:**
- macOS (uses `sips` command)
- Input PNG file (preferably 1024x1024)

**Output:**
- `AppIcon.appiconset/` directory with 18 icon files
- `Contents.json` for Xcode integration

## Setup

1. Place `.toml` files in `.gemini/commands/` directory
2. Use commands with `/command-name` syntax in Gemini CLI