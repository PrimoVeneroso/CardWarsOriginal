# Adventure Time: Card Wars

*Adventure Time: CARD WARS* — Modernized port and revival for **Linux Standalone (x86_64)**, **Windows (x86_64)**, and **Android (ARM64)**.

Floop the Pig! It's Adventure Time CARD WARS! Play the game inspired by the Adventure Time episode, 'Card Wars'! Summon creatures and cast spells to battle your way to victory.

---

## 🌟 Highlights & Features of this Repository

- **Native Standalone Linux (x86_64)**: Runs natively on modern Linux distributions with OpenGL/Vulkan GPU acceleration without Wine or emulators.
- **Updated Windows Standalone (x86_64)**: Recompiled with Unity 6, bringing full LAN multiplayer, widescreen display fixes, and content mods to PC.
- **Modern Android Support (ARM64 / IL2CPP)**: Fully compatible with modern 64-bit-only devices running Android 13, 14, 15, and newer.
- **Cross-Platform Real-Time LAN Multiplayer**: Replaces discontinued official servers with a local Wi-Fi / LAN lobby to battle friends across Windows, Linux, and Android on the same network.
- **Unlocked Content & Turbo Mode**: Integrated mod supporting all cards, heroes, dungeons, customizable profiles, and faster gameplay pacing.
- **Unity 6 & Unity 2022.3 LTS Compatibility**: Codebase updated to modern C# standards; resolved all Roslyn compilation issues, modern `EntityId` migrations, and updated AssetDatabase APIs.

---

## 📦 Downloads (Releases)

All pre-built binaries are available under the **[Releases](https://github.com/PrimoVeneroso/CardWarsOriginal/releases)** section:

| Platform | Package | Architecture | Description |
| :--- | :--- | :--- | :--- |
| 🐧 **Linux** | `CardWars-Linux-x86_64.tar.gz` | `x86_64` | Native ELF standalone binary (run with `./card_wars_linux.x86_64`) |
| 🪟 **Windows** | `CardWars-Windows-x86_64.zip` | `x86_64` | Standalone executable with LAN multiplayer (run `Card Wars.exe`) |
| 📱 **Android** | `card_wars_v10.12.13.apk` | `arm64-v8a` | APK for modern 64-bit Android smartphones & tablets |

* [Android ARM64 APK Source & Updates (Thecris28)](https://github.com/Thecris28/Card-Wars-ARM64-Android/releases)
* [Legacy Windows Version (ThugRod)](https://github.com/ThugRod/CardWarsOriginal/releases/download/latest/CardWars-Windows.zip)

---

## 🎮 Launching the Game

### Linux Standalone
Extract `CardWars-Linux-x86_64.tar.gz`, then in a terminal run:
```bash
chmod +x card_wars_linux.x86_64
./card_wars_linux.x86_64
```
*(Or simply double-click `card_wars_linux.x86_64` in your desktop file manager).*

### Windows Standalone
Extract `CardWars-Windows-x86_64.zip`, then double-click:
```text
Card Wars.exe
```

---

## 🛠️ Building from Source

1. Open the project in **Unity Hub** using **Unity 2022.3 LTS** or **Unity 6 (6000.x)**.
2. Open **File > Build Profiles**:
   - **For Linux**: Select *Linux*, choose architecture *x86_64*, and click **Build**.
   - **For Windows**: Select *Windows*, choose architecture *x86_64*, and click **Build**.
   - **For Android**: Select *Android* (ensure Android Build Support, OpenJDK, and NDK modules are installed) and click **Build**.

---

## 🏆 Credits & Acknowledgements

This revival is a community-driven preservation effort. Sincere thanks to everyone who contributed to keeping this beloved game alive:

- **Cartoon Network & Kung Fu Factory**: The original creators, artists, voice actors, and developers of *Adventure Time: Card Wars*. All intellectual property, trademarks, characters, music, and art assets belong to them.
- **[ThugRod](https://github.com/ThugRod)**: For the foundational decompilation work, restoring the Unity project, fixing shader compatibility, and providing the initial Windows port.
- **[yahirmonogatar12](https://github.com/yahirmonogatar12)**: For engineering real-time LAN multiplayer, implementing the unlocked-content mod, landscape viewport adaptations, and ARM64 headless export tools.
- **[Thecris28](https://github.com/Thecris28)**: For ongoing maintenance, publishing modern Android ARM64 builds, and authoring the Card Wars Save Decoder.
- **[PrimoVeneroso](https://github.com/PrimoVeneroso)**: For porting, resolving compilation errors on Unity 6, and producing the modernized standalone GNU/Linux and Windows x86_64 releases.
