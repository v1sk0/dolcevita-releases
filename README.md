# Dolce Vita Mobile Releases

APK releases for Dolce Vita Mobile app.

## Latest Version: v3.63

**Download:** [DolceVitaMobile-v3.63.apk](https://github.com/v1sk0/dolcevita-releases/releases/download/v3.63/DolceVitaMobile-v3.63.apk)

## Changelog

**v3.63** (2026-01-11)
- Add: Vremenska zaključanost popisa (4 sata)
- Add: Admin može otključati zaključan popis
- Fix: Skriveno dugme Obriši za završene popise

**v3.62** (2026-01-11)
- Fix: Brisanje popisa sada radi

**v3.61** (2026-01-11)
- Clean build

**v3.60** (2026-01-11)
- Fix: Prethodni popisi lista

**v3.59** (2026-01-11)
- Fix: Popis artikli prikaz

**v3.58** (2026-01-11)
- Fix: Version update check

**v3.57** (2026-01-10)
- Fix: Popis sync

**v3.48** (2026-01-08)
- Popis scanner identican kao Prijem

**v3.32** (2026-01-08)
- Popis inventara modul
- Scanner za barcode
- Offline podrska

## Auto-Update

Aplikacija automatski proverava novu verziju pri svakom pokretanju.
Podaci se citaju iz `apk/version.json` fajla preko GitHub API-ja.

## Struktura

```
dolcevita-releases/
├── apk/
│   ├── DolceVitaMobile-v3.63.apk   # Najnoviji APK
│   ├── DolceVitaMobile-v3.62.apk   # Prethodne verzije...
│   └── version.json                 # Verzija info (APP ČITA OVAJ FAJL)
├── README.md
└── version.json                     # Kopija (ignorisati)
```

**VAŽNO:** Aplikacija čita `apk/version.json` - uvek ažurirati taj fajl!