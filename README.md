# JDownloader Fluent Theme  
A sleek, Fluent-style dark theme for **JDownloader 2** with **Mica Effect** support.

![Screenshot](https://github.com/ikoshura/JDownloader-Fluent/blob/main/Jdownloadermica.png?raw=true)

## Features
- Fluent design with dark aesthetics for JDownloader 2.
- Mica Effect support for a dynamic, modern look on Windows.

## Installation

### Quick Installation
1. Download the files from the repository.
2. Copy them to the following locations:

**File Paths:**
```
%LOCALAPPDATA%\JDownloader 2.0\cfg\laf\FlatMacDarkLaf.json
```
```
%LOCALAPPDATA%\JDownloader 2.0\cfg\org.jdownloader.settings.GraphicalUserInterfaceSettings.json
```

**Note:** The folder name might vary (e.g., it could be `JDownloader 2` instead of `JDownloader 2.0`). Please check and adjust accordingly.

### Manual Installation

#### 1. Apply Theme in JDownloader:
1. Open **Settings** in JDownloader.
2. In the left sidebar, select **Advanced Settings**.
3. In the search field, type `LookAndFeelTheme`.
4. Set **`GraphicalUserInterfaceSettings: Look and Feel Theme`** to `FLATLAF_MAC_DARK`.
5. In the search field, type `Color Background`.
6. Set the following colors:
   - **`LAFSettings: Color For Table Package Row Background`**: `00000000` (RGB `000000`, Alpha `0`).
   - **`LAFSettings: Color For Table Alternate Row Background`**: `00000000` (RGB `000000`, Alpha `0`).
   - **`LAFSettings: Color For Panel Background`**: `fe000000` (RGB `000000`, Alpha `254`).
   - **`LAFSettings: Color For Table Mouse Over Rows Background`**: `8237a5ff` (RGB `37A5FF`, Alpha `100`).
   - **`LAFSettings: Color For Table Selected Rows Background`**: `8237a5ff` (RGB `37A5FF`, Alpha `130`).
7. In the search field, type `Color Foreground`, then change all black and white values to **white**.
8. In the search field, type `Color Text`, then change all colors to **white**.
9. In the search field, type `Window Decoration`.
10. Enable **`LAFSettings: Window Decoration`**.

#### 2. Enable Mica Effect:
1. Install [MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone).
2. Add **JDownloader 2** to the **MicaForEveryone** process rule to enable Mica support.
3. Enable **Extend Frame Into Client Area**.
4. Restart JDownloader to apply the changes.

### <sub>Upcoming Features</sub>
<sub>1. Add Mica effect support to the Header/Titlebar.</sub><br>
<sub>2. Update icons and symbols to match a more modern, Windows 11-style aesthetic.</sub>
