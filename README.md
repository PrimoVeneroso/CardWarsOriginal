# Card Wars

*Adventure Time: CARD WARS* - Porting moderno per Android (ARM64) e Linux Standalone Nativo (x86_64).

Floop the Pig! It's Adventure Time CARD WARS! Play the game inspired by the Adventure Time episode, 'Card Wars'! Summon creatures and cast spells to battle your way to victory.

---

## 🌟 Novità e Migliorie di questo repository

- **Versione Linux Nativa (x86_64)**: giocabile nativamente su distribuzioni Linux moderne senza bisogno di emulatori o Wine.
- **Supporto Android Moderno (ARM64 / IL2CPP)**: compatibile con Android 13, 14, 15+ sui telefoni moderni a 64-bit.
- **Multigiocatore LAN in tempo reale**: sostituisce i server online originali (spenti) con una lobby locale (LAN / Wi-Fi) per giocare con altri amici.
- **Mod Sblocco Contenuti & Turbo Mode**: carte, eroi e dungeon sbloccati con supporto a profili e bilanciamento personalizzabile.
- **Compatibilità con Unity 6 e Unity 2022.3 LTS**: codice aggiornato e correzione delle funzioni e attributi deprecati (Roslyn, EntityId, Texture Importers).

---

## 📦 Download

* **[Versione Linux Nativa (x86_64)](https://github.com/PrimoVeneroso/CardWarsOriginal/releases)**
* **[Versione Android ARM64](https://github.com/Thecris28/Card-Wars-ARM64-Android/releases)**
* **[Versione Windows (Legacy)](https://github.com/ThugRod/CardWarsOriginal/releases/download/latest/CardWars-Windows.zip)**

---

## 🐧 Eseguire la versione Linux

Dopo aver scaricato o compilato la cartella di build:
```bash
chmod +x card_wars_linux.x86_64
./card_wars_linux.x86_64
```

---

## 🛠️ Compilazione da codice sorgente

1. Apri la cartella del progetto con **Unity Hub** (versione supportata: Unity 2022.3 LTS oppure Unity 6).
2. Vai su **File > Build Profiles**:
   - Per **Linux**: seleziona *Linux*, architettura *x86_64* e premi **Build**.
   - Per **Android**: seleziona *Android* (assicurati di aver installato i moduli Android Build Support, OpenJDK e NDK) e premi **Build**.

---

## 🏆 Crediti e Riconoscimenti

Un sincero ringraziamento a tutte le persone e community che hanno reso possibile preservare e far rivivere questo gioco:

- **Cartoon Network & Kung Fu Factory**: Sviluppatori e ideatori originali del gioco. Tutti i diritti, loghi, personaggi, musiche e asset appartengono a loro.
- **[ThugRod](https://github.com/ThugRod)**: Per il fondamentale lavoro iniziale di decompilazione, ripristino del codice sorgente su Unity e prima versione PC Windows.
- **[yahirmonogatar12](https://github.com/yahirmonogatar12)**: Per l'implementazione del multigiocatore LAN in tempo reale, la mod di sblocco carte/contenuti, il supporto a risoluzioni orizzontali e gli script di esportazione ARM64.
- **[Thecris28](https://github.com/Thecris28)**: Per il mantenimento e pubblicazione continuativa delle build Android ARM64 e del tool Card Wars Save Decoder.
- **[PrimoVeneroso](https://github.com/PrimoVeneroso)**: Per il porting, risoluzione errori di compatibilità su Unity 6 e creazione della build nativa per Linux x86_64.
