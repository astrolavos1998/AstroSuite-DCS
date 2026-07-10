<div align="center">

🇬🇧 [English](#english) &nbsp;&nbsp;&nbsp; 🇬🇷 [Ελληνικά](#greek)

</div>

---

<a name="english"></a>

# AstroSuite-DCS 4.5

| # | Tool | Version | Description |
|---|------|---------|-------------|
| 1 | 🎛️ [**Mods Manager**](#en-mods-manager) | v.2.6 | 3-panel community mod management (Core / DB / Saved Games) |
| 2 | 🧹 [**Clear Trash Utility**](#en-clear-trash) | v.1.2 | Delete temporary DCS files (shaders, logs, cache) |
| 3 | 🗺️ [**Moving Map**](#en-moving-map) | v.3.4 | Transfer DCS map folders to external storage (symlinks) |
| 4 | 🗺 [**Mission Map Converter**](#en-mission-map) | v.1.5 | Copy & transfer a `.miz` mission to a different theatre |
| 5 | 💾 [**Persistence Manager**](#en-persistence) | v.1.3 | Enable/Disable DCS persistence file recording |
| 6 | 📹 [**Recorder Management**](#en-recorder) | v.1.2 | Toggle DCS Track Files & Tacview recording |
| 7 | 🎙️ [**Radio Menu Creator 2**](#en-radio-menu) | v.2.0 | Tree editor for radio menus — undo/redo, export/import LUA |
| 8 | 📡 [**GCI-DCS**](#en-gci) | — | GitHub Lua script for GCI simulation |

---

## Changelog

### v.4.5 — 09.07.2026

<a name="en-mods-manager"></a>
- **🎛️ Mods Manager v.2.6** — complete redesign:
  - 3-panel layout: Core | Mods DB | Saved Games
  - Source (Mods Database) is read-only — never modified
  - Community mods only — DCS built-in content is ignored
  - Active mods shown in destination panels; inactive in Source panel
  - Grayed-out items in Source panel = already active somewhere
  - 🔄 Refresh button added

<a name="en-mission-map"></a>
- **🗺 Mission Map Converter** → v.1.5

<a name="en-persistence"></a>
- **💾 Persistence Manager** → v.1.3

<a name="en-recorder"></a>
- **📹 Recorder Management** → v.1.2
- Refactored into a proper Python package (`astrosuite/`)
- Each tool is now a standalone module under `astrosuite/tools/`
- Entry point: `python -m astrosuite.main`
- Bug fixes

### v.4.3 — 08.07.2026
- Bug fixes, more friendly environment

### v.4.0 — 05.07.2026
- Added **Mods Manager**
- Bug fixes

### v.4.0 (v.3) — 04.04.2026
- Added ability to disable/enable recording in DCS World and Tacview

### v.4.0 (v.2) — 07.03.2026
- Integration of all applications into one suite
- New GUI with a better and more functional look

<a name="en-clear-trash"></a>

### v.1.18 / v.2.26 — 17.01.2026
- **🧹 Clear Trash v.1.18**: automatic GPU detection (NVIDIA), NVIDIA Shader Cache cleanup (DXCache / GLCache), new GUI

<a name="en-radio-menu"></a>
- **🎙️ Radio Menu Creator 2 v.2.26**: live LUA preview in "PREVIEW / PASTE LUA CODE:" section

### v.2.25 — 12.01.2026
- **🎙️ Radio Menu Creator 2**: "Load LUA file" button, One-Liners support, Space Tolerance, auto-fix orphaned commands, sm1/sm2 support, improved TreeView

<a name="en-moving-map"></a>
<a name="en-gci"></a>

### v.1.09 / v.3.09 — 05.01.2026
- **📡 GCI-DCS v.5.18** integrated — Lua script for ground controlled interception
- **🗺️ Moving Map v.3.09**: new interface, EN/GR, Dark/Light theme
- **Clear Trash v.1.16**: EN/GR, Dark/Light theme
- **DCS-Persistence v.2.04**: new interface
- **Radio Menu Creator 2 v.2.24**: fix LUA save bug, EN/GR, Dark/Light theme

### v.2.19 — 02.01.2026
- **🎙️ Radio Menu Creator 2**: fix display when menu/submenu missing, undo/redo up to 10 times

---

## Installation & Use

| | |
|---|---|
| **Download** | Get the latest version from [Releases] |
| **Installation** | Run `AstroSuiteInstall.exe` |
| **Permissions** | Run as Administrator for Symlinks & file cleanup |

> ⚠️ **WARNING:** Use of the applications is at your own risk.

---

**AstroSuite 4.5®  ·  2026©  ·  LOCK-ON GREECE  ·  by =GR= Astr0**
*with support from Gemini AI & Claude AI*

---
---

<a name="greek"></a>

# AstroSuite-DCS 4.5

| # | Εργαλείο | Έκδοση | Περιγραφή |
|---|----------|--------|-----------|
| 1 | 🎛️ [**Mods Manager**](#gr-mods-manager) | v.2.6 | 3-panel διαχείριση community mods (Core / DB / Saved Games) |
| 2 | 🧹 [**Clear Trash Utility**](#gr-clear-trash) | v.1.2 | Διαγραφή προσωρινών αρχείων DCS (shaders, logs, cache) |
| 3 | 🗺️ [**Moving Map**](#gr-moving-map) | v.3.4 | Μεταφορά χαρτών DCS σε εξωτερικό δίσκο (symlinks) |
| 4 | 🗺 [**Mission Map Converter**](#gr-mission-map) | v.1.5 | Αντιγραφή & μεταφορά αποστολής `.miz` σε νέο θέατρο |
| 5 | 💾 [**Persistence Manager**](#gr-persistence) | v.1.3 | Ενεργοποίηση/Απενεργοποίηση persistence αρχείων DCS |
| 6 | 📹 [**Recorder Management**](#gr-recorder) | v.1.2 | Toggle Track Files DCS & Tacview |
| 7 | 🎙️ [**Radio Menu Creator 2**](#gr-radio-menu) | v.2.0 | Tree editor για radio menus — undo/redo, export/import LUA |
| 8 | 📡 [**GCI-DCS**](#gr-gci) | — | GitHub Lua script για προσομοίωση GCI |

---

## Changelog

### v.4.5 — 09.07.2026

<a name="gr-mods-manager"></a>
- **🎛️ Mods Manager v.2.6** — πλήρης επανασχεδιασμός:
  - 3-panel διάταξη: Core | Mods DB | Saved Games
  - Η Βάση Mods (Source) είναι μόνο ανάγνωσης — δεν τροποποιείται ποτέ
  - Μόνο community mods — το built-in DCS content αγνοείται
  - Ενεργά mods εμφανίζονται στα destination panels· ανενεργά στο Source
  - Γκριζαρισμένα στοιχεία στο Source = ήδη ενεργά αλλού
  - Προστέθηκε κουμπί 🔄 Refresh

<a name="gr-mission-map"></a>
- **🗺 Mission Map Converter** → v.1.5

<a name="gr-persistence"></a>
- **💾 Persistence Manager** → v.1.3

<a name="gr-recorder"></a>
- **📹 Recorder Management** → v.1.2
- Αναδιάρθρωση σε Python package (`astrosuite/`)
- Κάθε εργαλείο είναι πλέον αυτόνομο module στο `astrosuite/tools/`
- Σημείο εκκίνησης: `python -m astrosuite.main`
- Διορθώσεις σφαλμάτων

### v.4.3 — 08.07.2026
- Διορθώσεις σφαλμάτων, πιο φιλικό περιβάλλον

### v.4.0 — 05.07.2026
- Προσθήκη **Mods Manager**
- Διορθώσεις σφαλμάτων

### v.4.0 (v.3) — 04.04.2026
- Προστέθηκε η δυνατότητα απενεργοποίησης/ενεργοποίησης εγγραφής σε DCS World και Tacview

### v.4.0 (v.2) — 07.03.2026
- Ενσωμάτωση όλων των εφαρμογών σε μία
- Νέο GUI με καλύτερη και πιο λειτουργική εμφάνιση

<a name="gr-clear-trash"></a>

### v.1.18 / v.2.26 — 17.01.2026
- **🧹 Clear Trash v.1.18**: αυτόματη ανίχνευση GPU (NVIDIA), καθαρισμός NVIDIA Shader Cache (DXCache / GLCache), νέο GUI

<a name="gr-radio-menu"></a>
- **🎙️ Radio Menu Creator 2 v.2.26**: άμεση προεπισκόπηση LUA στην ενότητα "ΠΡΟΕΠΙΣΚΟΠΗΣΗ / ΕΠΙΚΟΛΛΗΣΗ ΚΩΔΙΚΟΥ LUA:"

### v.2.25 — 12.01.2026
- **🎙️ Radio Menu Creator 2**: κουμπί "Φόρτωση αρχείου LUA", υποστήριξη One-Liners, Space Tolerance, αυτόματη διόρθωση ορφανών εντολών, υποστήριξη sm1/sm2, βελτιωμένο TreeView

<a name="gr-moving-map"></a>
<a name="gr-gci"></a>

### v.1.09 / v.3.09 — 05.01.2026
- **📡 GCI-DCS v.5.18** ενσωματώθηκε — Script Lua για επίγεια ελεγχόμενη αναχαίτιση
- **🗺️ Moving Map v.3.09**: νέα διεπαφή, EN/GR, σκοτεινό/ανοιχτό θέμα
- **Clear Trash v.1.16**: EN/GR, σκοτεινό/ανοιχτό θέμα
- **DCS-Persistence v.2.04**: νέα διεπαφή
- **Radio Menu Creator 2 v.2.24**: διόρθωση αποθήκευσης LUA, EN/GR, σκοτεινό/ανοιχτό θέμα

### v.2.19 — 02.01.2026
- **🎙️ Radio Menu Creator 2**: διόρθωση εμφάνισης όταν λείπει μενού/υπομενού, undo/redo έως 10 φορές

---

## Εγκατάσταση & Χρήση

| | |
|---|---|
| **Λήψη** | Κατεβάστε την τελευταία έκδοση από τα [Releases] |
| **Εγκατάσταση** | Εκτελέστε το `AstroSuiteInstall.exe` |
| **Δικαιώματα** | Εκτελέστε ως Διαχειριστής για Symlinks & εκκαθάριση |

> ⚠️ **ΠΡΟΕΙΔΟΠΟΙΗΣΗ:** Η χρήση των εφαρμογών γίνεται με δική σας ευθύνη.

---

**AstroSuite 4.5®  ·  2026©  ·  LOCK-ON GREECE  ·  από =GR= Astr0**
*με υποστήριξη από Gemini AI & Claude AI*
