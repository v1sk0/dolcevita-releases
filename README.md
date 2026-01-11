# Dolce Vita Mobile Releases

APK releases for Dolce Vita Mobile app.

## Latest Version: v3.7

**Download:** [DolceVitaMobile-v3.7.apk](https://github.com/v1sk0/dolcevita-releases/blob/main/apk/DolceVitaMobile-v3.7.apk?raw=true)

## Changelog

**v3.7** (2026-01-11)
- Fix: Ispravljena JavaScript greška - dupla deklaracija varijable
- Fix: Login sada radi ispravno

**v3.69** (2026-01-11)
- Fix: Delete dugme za admina sada radi ispravno
- Fix: Poboljšano rukovanje greškama pri brisanju popisa

**v3.68** (2026-01-11)
- Fix: Agregacija istih artikala u tabeli popisa
- Fix: Isti proizvod se objedinjuje u jednu stavku

**v3.67** (2026-01-11)
- Fix: Nastavi popis učitava postojeće stavke
- Fix: Ispravljen undefined error pri nastavku popisa

**v3.66** (2026-01-11)
- Fix: Nastavi dugme vidljivo dok popis nije zaključan
- UI: Collapsible popis lista sa chevron toggle

**v3.65** (2026-01-11)
- UI: Nova popis lista - grid layout, centrirano
- Add: Nastavi dugme za nastavak popisa

**v3.64** (2026-01-11)
- Update: APP_VERSION in app.js

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
- Popis scanner identičan kao Prijem

**v3.32** (2026-01-08)
- Popis inventara modul
- Scanner za barcode
- Offline podrška

## Auto-Update

Aplikacija automatski proverava novu verziju pri svakom pokretanju.
Podaci se čitaju iz `apk/version.json` fajla preko GitHub API-ja.

## Struktura

```
dolcevita-releases/
├── apk/
│   ├── DolceVitaMobile-v3.7.apk   # Najnoviji APK
│   ├── DolceVitaMobile-v3.69.apk   # Prethodne verzije...
│   └── version.json                 # Verzija info (APP ČITA OVAJ FAJL)
├── README.md
└── version.json                     # Kopija (ignorisati)
```

**VAŽNO:** Aplikacija čita `apk/version.json` - uvek ažurirati taj fajl!