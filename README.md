# 🗂️ Ludusavi Piracy Manifest

A **manifest** that provides **emulator related paths** for **Ludusavi**, including **Steam Cloud Save** and **Achievement** directories.


## 📥 How to Use
* Open Ludusavi and navigate to the **Other** tab.
* Scroll down to locate the **Manifest** section. 
* Make sure the Input Mode is set to **URL** (not File).
* Add the following **GitHub Raw URL**:

* https://raw.githubusercontent.com/DogancanYr/ludusavi-piracy-manifest/refs/heads/main/Piracy-manifest.yaml

* When you're done, Click the **Reload** (🔄) button next to **Manifest:**.  "

✅ If done correctly, you should see timestamps for `Checked:` and `Updated:`
<img width="1882" height="240" alt="Ekran görüntüsü 2025-11-21 224131" src="https://github.com/user-attachments/assets/a3af76b7-523c-43ea-b659-144ab30ecdf1" />

## 💾 File paths

| Emulator           | File Paths                                                                                                      |
|-------------------|-------------------|
| Goldberg Fork      | `%APPDATA%/GSE Saves`                                                                                        |
| Goldberg           | `%APPDATA%/Goldberg SteamEmu Saves`                                                                         |
| OnlineFix          | `%PUBLIC%/Documents/OnlineFix`                                                                              |
| EMPRESS            | `%APPDATA%/EMPRESS`, `%PUBLIC%/EMPRESS`                                                                  |
| Rune               | `%PUBLIC%/Documents/Steam/Rune`                                                                             |
| Codex              | `%PUBLIC%/Documents/Steam/Codex`, `%APPDATA%/Steam/CODEX`                                                |
| SkidRow            | `Documents/SkidRow`, `%LOCALAPPDATA%/skidrow`                                                         |
| SmartSteamEmu      | `%APPDATA%/SmartSteamEmu`                                                                                    |
| CreamApi           | `%APPDATA%/CreamApi`                                                                                         |
| UniverseLAN*        | **`<root>/**/UniverseLANData`**, `C:/GOG Games/**/UniverseLANData`, `D:/GOG Games/**/UniverseLANData`, `C:/Games/GOG Games/**/UniverseLANData`, `D:/Games/GOG Games/**/UniverseLANData` |

| ❗  |  Because UniverseLAN depends on the game installation, if your game is installed outside the default GOG games installation path or C:/ and D:/, add the main folder of your game(s) here if they are not in the default location.           | 
| ------------- |:-------------:|

## ✨ Want to add a new emulator or piracy related tool?  
Just open an **Issue** and provide:  

* The name of the emulator/tool.
* The location of its save or configuration files.

It will be added to the manifest as soon as possible!
