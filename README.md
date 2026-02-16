# Silence - Accessibility Mod

**Developer:** Lirin's Workshop

## About

This mod makes the game "Silence" fully accessible for blind and visually impaired players by adding audio cues, text-to-speech announcements, and automated assistance for visual puzzles.

## Installation

1. **Install MelonLoader 0.5.4** (if not already installed)
   - Download from: https://github.com/LavaGang/MelonLoader/releases/tag/v0.5.4
   - Run the installer and point it to your Silence game folder
   
2. **Install the Accessibility Mod**
   - Extract the mod package to your Silence game folder
   - The package includes:
     - `Mods` folder with `SilenceAccessibilityMod.dll` inside
     - TOLK DLLs (`dolapi.dll`, `nvdaControllerClient32.dll`, `SAAPI32.dll`) for screen reader support
   - These files should be in your game's root folder (e.g., `Steam\steamapps\common\Silence\`)
   
3. **Launch the game** - The mod will load automatically

## Features

### Dragon Shard Puzzle (Chapter 2)
- **F9 key**: Enable puzzle guidance when you reach the dragon
- Tracks your 19-step sequence automatically
- Announces each position as you collect energy
- **F8 key**: Repeat the last step reminder

### Character Form Changes
- Announces when Spot changes forms (Normal, Balloon, Flat)
- Helps you know which abilities are available

### Balance Minigame
- Audio feedback with quieter, more pleasant tones
- Helps you maintain balance without visual cues

### Flight Minigame (Chapter 4)
- Strong magnetic steering that guides you to cloud holes
- Audio cues when hitting good holes or bad clouds
- Automatic correction keeps you on course

### Lighthouse Star Puzzle (Final Chapter)
- **F key**: Toggle auto-aim to automatically target stars
- Auto-aim prioritizes white obstacle stars first, then constellation stars
- Announcements guide you through the puzzle progress
- **F8 key**: Get hints about current objective

### Additional Features
- Automatic clicking at cursor position (when possible)
- Text-to-speech for dialogue and important messages

## Controls

- **F9 key**: Enable Dragon Shard puzzle guidance
- **F key**: Toggle auto-aim in Lighthouse puzzle
- **F8 key**: Repeat hints for Dragon puzzle and Lighthouse puzzle
- **Arrow keys**: Navigate menus and move cursor
- **Mouse**: Still works normally for all interactions

## Support

If you encounter any issues or have suggestions, please report them on the mod's GitHub page.

---

**Note:** This mod requires MelonLoader v0.5.4 and is designed for the Windows version of Silence.
