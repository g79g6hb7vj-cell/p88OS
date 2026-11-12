# P88 OS (Project 88)

**P88 OS** è un sistema operativo leggero basato su Linux Mint XFCE, progettato specificamente per far risorgere e ottimizzare hardware datato (PC, laptop e dispositivi mobili) grazie a un sistema intelligente di gestione della memoria e di espansione RAM dinamica.

---

## 🚀 Caratteristiche Principali

- **Consumo Zero Sprechi:** Costruito su una base minimale XFCE per girare fluidamente anche su computer con pochissima RAM.
- **Espansione RAM On-Demand (P88 MemBoost):** Monitora in tempo reale la saturazione della RAM e attiva lo swap d'emergenza **solo quando la memoria fisica supera il 90%**, proteggendo i dischi da scritture inutili.
- **Rilevamento Intelligente del Dispositivo:** Riconosce automaticamente se è in esecuzione su un PC/Laptop (gestendo memorie USB ed esterne con avvisi sui rischi degli HDD meccanici) o su Mobile (sfruttando la memoria interna).
- **Gestione Multi-Dispositivo:** Possibilità di combinare più unità di supporto con una scala di priorità intelligente.

---

## 📂 Struttura del Progetto

```text
P88-OS/
├── p88-core/
│   ├── bin/             # Demoni e script principali (p88-memboost, p88-usb-prompt)
│   ├── config/          # File di configurazione predefiniti
│   └── udev/            # Regole per il rilevamento delle periferiche USB
├── install.sh           # Script di installazione automatica per Linux Mint / Ubuntu
└── README.md            # Documentazione del progetto
