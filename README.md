# Adventure Time: Card Wars

*Adventure Time: CARD WARS* — Modernized port for modern Android (ARM64) and Native Standalone Linux (x86_64).

Floop the Pig! It's Adventure Time CARD WARS! Play the game inspired by the Adventure Time episode, 'Card Wars'! Summon creatures and cast spells to battle your way to victory.

---

## 🌟 Highlights & Features of this Repository

- **Native Standalone Linux (x86_64)**: Runs natively on modern Linux distributions with OpenGL/Vulkan GPU acceleration without Wine or emulators.
- **Modern Android Support (ARM64 / IL2CPP)**: Fully compatible with 64-bit-only devices running Android 13, 14, 15, and newer.
- **Real-Time LAN Multiplayer**: Replaces the discontinued official online servers with a local Wi-Fi / LAN lobby to play with friends on the same network.
- **Unlocked Content & Turbo Mode**: Optional mod support enabling all cards, heroes, dungeons, customizable profiles, and faster gameplay pacing.
- **Unity 6 & Unity 2022.3 LTS Compatibility**: Codebase updated to modern C# standards; resolved all Roslyn compilation issues, modern `EntityId` migrations, and updated AssetDatabase APIs.

---

## 📦 Downloads

* **[Latest Native Linux Release (x86_64)](https://github.com/PrimoVeneroso/CardWarsOriginal/releases)**
* **[Latest Android APK (ARM64)](https://github.com/Thecris28/Card-Wars-ARM64-Android/releases)**
* **[Windows Standalone (Legacy)](https://github.com/ThugRod/CardWarsOriginal/releases/download/latest/CardWars-Windows.zip)**

---

## 🐧 Running the Native Linux Build

After downloading or compiling the standalone package:
```bash
chmod +x card_wars_linux.x86_64
./card_wars_linux.x86_64
```

---

## 🛠️ Building from Source

1. Open the project in **Unity Hub** using **Unity 2022.3 LTS** or **Unity 6 (6000.x)**.
2. Open **File > Build Profiles**:
   - **For Linux**: Select *Linux*, choose architecture *x86_64*, and click **Build**.
   - **For Android**: Select *Android* (ensure Android Build Support, OpenJDK, and NDK modules are installed) and click **Build**.

---

## 🏆 Credits & Acknowledgements

This revival is a community-driven preservation effort. Sincere thanks to everyone who contributed to keeping this beloved game alive:

- **Cartoon Network & Kung Fu Factory**: The original creators, artists, voice actors, and developers of *Adventure Time: Card Wars*. All intellectual property, trademarks, characters, music, and art assets belong to them.
- **[ThugRod](https://github.com/ThugRod)**: For the foundational decompilation work, restoring the Unity project, fixing shader compatibility, and providing the initial Windows port.
- **[yahirmonogatar12](https://github.com/yahirmonogatar12)**: For engineering real-time LAN multiplayer, implementing the unlocked-content mod, landscape viewport adaptations, and ARM64 headless export tools.
- **[Thecris28](https://github.com/Thecris28)**: For ongoing maintenance, publishing modern Android ARM64 builds, and authoring the Card Wars Save Decoder.
- **[PrimoVeneroso](https://github.com/PrimoVeneroso)**: For porting, resolving compilation errors on Unity 6, and producing the native standalone GNU/Linux x86_64 release.
