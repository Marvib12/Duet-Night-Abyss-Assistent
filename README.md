# Duet Night Abyss Assistent

Companion app for **Duet Night Abyss** (Windows): Demon Wedges, builds, priority list, Geniemon collection and Covert Commissions – with hotkey recognition right in the game. Runs entirely on your PC.

## Download

👉 **[Download the latest version](../../releases/latest)** – under “Assets”, get `DnaAssistant.exe`.

- No installation needed, just run it.
- The app asks for **administrator rights** on startup. The game runs with administrator rights; without them, hotkeys and screen capture don't reach the game.
- The app tells you about new versions on startup.
- Windows SmartScreen may warn on first launch (“Unknown publisher”) – click “More info › Run anyway”.

## Features

| Area | What it does |
|---|---|
| **Demon Wedges** | All wedges with search and filters (category, element, rarity, polarity, source); counter for +10 copies; rarity color in the preview. |
| **Categories & goals** | Wanted amount per category or single wedge (e.g. 1 or 4), sort by done/open, max level (gold +10, otherwise +5). |
| **Builds** | Import via boarhat link/code, from boarhat presets or from a screenshot of the wedge set. Choose character, melee and ranged weapon, progress like “3/10 wedges done”, add missing wedges to the priority list in one click, share builds as a link. |
| **Priority list** | Wedges you need next – shown in game via hotkey (default **F7**), including where to get them. |
| **Geniemons** | Collection per variant (Miraculous, Ardent, Shiny) with wanted amount, grouped and expandable. Battle pass Geniemons without a limit. |
| **Covert Commission** | Current modes of all regions, notification with sound for your modes in your region, share settings via code. |
| **Action log** | Every change can be undone; **F9** reverts the last hotkey action. |

### Hotkey F8 in game

- **Wedge detail view:** recognizes wedge, rarity and level and counts it at max level.
- **Geniemon view:** counts the variant when it's at max level (Lv. 60/60, three stars).
- **Catch screen:** tells you whether you still need this Geniemon.

**Tips for good recognition**

- Play in **windowed or borderless mode** (in exclusive fullscreen the capture can be black).
- Ideally install the English Windows text recognition – in an **administrator PowerShell**:
  ``` 
  Add-WindowsCapability -Online -Name "Language.OCR~~~en-US~0.0.1.0"
  ```

### Autostart (optional)

In the settings under **Autostart**:

- **Steam:** paste the shown launch option in Steam at Duet Night Abyss under *Properties › Launch options*.
- **Launcher:** create the desktop shortcut “DNA Assistant + Launcher” and/or start with Windows.

## Languages

Deutsch, English, Français, Español, Italiano, Português, Polski, Türkçe, Русский, Українська, 日本語, 한국어, 简体中文

## Data & privacy

All data (progress, builds, settings) stays on your PC in `%LocalAppData%\DnaAssistant`. The only things fetched online are public game data from [boarhat.gg](https://boarhat.gg/games/duet-night-abyss/), the Covert Commissions from a web API and new app versions here on GitHub.

## Problems or ideas?

Feel free to report them via [Issues](../../issues) – for recognition problems, please attach a screenshot of the affected view.

---

Unofficial fan project, not affiliated with the developers or publishers of Duet Night Abyss.
