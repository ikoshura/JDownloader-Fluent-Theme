# JDownloader Fluent Theme  
Fluent-style dark theme for **JDownloader 2** with **Mica Effect** support.

![Screenshot](https://github.com/ikoshura/JDownloader-Fluent-Theme/blob/main/Assets/MicaUpdate.png)

---

## Features
- Modern Fluent design with dark aesthetics.
- Mica Effect support for a dynamic & polished look on Windows.

---

## Installation Guide

### Quick Installation
1. **Download** the files from this repository.
2. **Replace** the existing configuration files with the downloaded ones:
   
   **JSON Configuration File Paths:**
   ```
   %LOCALAPPDATA%\JDownloader 2\cfg\laf\FlatMacDarkLaf.json
   ```
   ```
   %LOCALAPPDATA%\JDownloader 2\cfg\org.jdownloader.settings.GraphicalUserInterfaceSettings.json
   ```

   > **Note:** Your folder name might differ (e.g., `JDownloader 2.0`). Adjust as needed.

3. Navigate to `%LOCALAPPDATA%\JDownloader 2\libs\laf`.
4. Create a backup of `flatlaf.jar` (e.g., rename it to `flatlaf.jar.bak`).
5. Open `flatlaf.jar` with a tool like **7-Zip**.
6. Go to `\com\formdev\flatlaf\themes\` inside the archive.
7. Replace `FlatMacDarkLaf.properties` with the one from this repository.
8. Save changes when prompted.

### Manual Installation

#### 1. Apply Theme in JDownloader:
1. Open **Settings** in JDownloader.
2. In the left sidebar, select **Advanced Settings**.
3. Search for `LookAndFeelTheme`.
4. Set **`GraphicalUserInterfaceSettings: Look and Feel Theme`** to `FLATLAF_MAC_DARK`.
5. Search for `Color Background` and apply these values:

   | **Setting**                                      | **HEX**      | **RGB**      | **Alpha** |
   |--------------------------------------------------|--------------|--------------|-----------|
   | Color For Table Package Row Background           | `00000000`   | `000000`     | `0`       |
   | Color For Table Alternate Row Background         | `00000000`   | `000000`     | `0`       |
   | Color For Panel Background                       | `fe000000`   | `000000`     | `254`     |
   | Color For Table Mouse Over Rows Background       | `32FFFFFF`   | `FFFFFF`     | `50`     |
   | Color For Table Selected Rows Background         | `32FFFFFF`   | `FFFFFF`     | `50`     |

6. Search for `Color For Table Row Gap` and set it to:

   | **Setting**                      | **HEX**      | **RGB**      | **Alpha** |
   |----------------------------------|--------------|--------------|-----------|
   | Color For Table Row Gap          | `00000000`   | `000000`     | `0`       |

7. Search for `Color Foreground` and change all black/white values to **white**.
8. Search for `Color Text` and set all colors to **white**.
9. Search for `Window Decoration` and enable **`LAFSettings: Window Decoration`**.
10. Navigate to `%LOCALAPPDATA%\JDownloader 2\libs\laf`.
11. Create a backup of `flatlaf.jar` (e.g., rename it to `flatlaf.jar.bak`).
12. Open `flatlaf.jar` with a tool like **7-Zip**:
    - Go to `\com\formdev\flatlaf\themes\`.
    - Open `FlatMacDarkLaf.properties` in a text editor.
    - follow this configuration:
      ```
      @nsTextBackgroundColor = #202020
      @nsControlBackgroundColor = #202020
      @nsControlAccentColor = #fffffff1   # You can replace this with your preferred accent color
      @buttonBackground = #00000001
      @accentFocusColor = #00000000
      Component.borderColor = #00000000
      Component.disabledBorderColor = #00000000
      ```
    - Save and close the editor.
    - Accept prompts to update the archive.

   > **Tip:** You can preview the advanced color settings below:
   <details closed>
      
   > ![Colors Preview](https://github.com/user-attachments/assets/fa011986-ed4f-4f3d-9d23-0203067890a0)
  
   </details>

#### 2. Enable Mica Effect:
1. Install [MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone).
2. Add **JDownloader 2** to the **MicaForEveryone** process rules.
3. Enable **Extend Frame Into Client Area**.
4. Restart JDownloader to apply changes.

---

## Upcoming Features
1. **Mica effect support** for the Header/Titlebar.
2. Updated icons and symbols for a modern Windows 11-style look.

---

