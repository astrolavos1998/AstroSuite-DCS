# 🚀 AstroSuite - DCS v.1.10


<a name="english"></a>
## 🇺🇸 English Version	|	[Ελληνική Έκδοση](#ελληνικά)

## Update 17.01.2026
* CLEAR TRASH - DCS v.1.18
	*Automatic Hardware Detection (GPU Detection): The new version recognizes whether your system has an NVIDIA or AMD graphics card.
	*Cleaning NVIDIA Shader Cache: Added function to automatically delete DXCache and GLCache folders (with try-except system for files in use).
	*AMD Software Support: Add a special button to open the AMD software and display instructions for manual cache reset.
	*New GUI.

## Update 12.01.2026
* RADIO MENU CREATOR 2 - DCS v.2.25
	* Add buton "Load LUA file".
	* One-Liners Support: You can paste several commands (c1, c2, c3...) on the exact same line and the program will recognize them all separately.
	* Space Tolerance: Recognizes commands even if there is a space before the parenthesis (eg addCommand (...)) or between the commas.
	* Automatic Correction of Orphaned Commands: If a command refers to a sub-menu that does not exist (eg sm1), the program automatically changes it to nil so that it appears normally in the RADIO MENU STRUCTURE.
	* sm1/sm2 support: No longer limited to specific names (m1, m2). It reads any variable name you use in your LUA code.
	* Improved TreeView: "Orphaned" commands now appear at the top of the tree instead of disappearing, so you can edit them immediately.

## Update 05.01.2026
* CLEAR TRASH - DCS v.1.16
	* Add English and Greek language.
	* Add Dark and Light Theme.
* AstroSuite - DCS v.1.09
	* Add GCI - DCS v.5.18 a lua script that simulates Ground-Controlled Interception (GCI) for DCS World Mission Editor.
* MOVING MAP - DCS v.3.09
	* Change application interface.
	* Add English and Greek language.
	* Add Dark and Light Theme.
* DCS-PERSISTENCE v.2.04
	* Change application interface.
* RADIO MENU CREATOR 2 - DCS v.2.24
	* Fix bag for save lua file.
	* Add English and Greek language.
	* Add Dark and Light Theme.

### Update 02.01.2026
* RADIO MENU CREATOR 2 - DCS v.2.19
	* Fixed if it doesn't have a main menu or submenu to show the radio menu code correctly.
	* Added the ability to redo/undo up to 10 times forward/backward.

### Description
**AstroSuite - DCS** is a comprehensive open-source toolset designed exclusively for **Digital Combat Simulator (DCS World)** pilots. Its purpose is to optimize simulator performance, manage storage space, and simplify mission creation.

### 🛠️ Included Applications

* **🧹 CLEAR TRASH - DCS:** Automatically deletes temporary cache folders (`fxo`, `metashaders2`), old logs, and tracks. Eliminates stutters and fixes visual bugs after game or driver updates.
* **🗺️ MOVING MAP - DCS:** Manages DCS terrain storage. It moves bulky map folders to another drive (e.g., HDD or larger NVMe) using **Symbolic Links (Symlinks)** without affecting game functionality.
* **💾 PERSISTENCE MANAGER - DCS:** Manages mission scripting environment by enabling/disabling the de-sanitization of `MissionScripting.lua`. Allows advanced scripts to save progress to external files.
* **🎙️ RADIO MENU CREATOR - DCS:** A GUI tool for mission designers to quickly create custom radio menus (F10 Menu) without manual LUA coding.

### 🚀 Installation & Usage
1.  **Download:** Get the latest version from [Releases].
2.  **Folder Structure:** Place the application executables inside a subfolder named `Applications`.
3.  **Permissions:** Run `AstroSuite.exe` as **Administrator** to ensure Symlinks and file cleanup work correctly.


**WARNING: Use of the applications is at your own risk.**
---

<a name="ελληνικά"></a>
## 🇬🇷 Ελληνική Έκδοση	|	[English Version](#english)

## Ενημέρωση 17.01.2026
* CLEAR TRASH - DCS v.1.18
	*Αυτόματη ανίχνευση υλικού (Ανίχνευση GPU): Η νέα έκδοση αναγνωρίζει εάν το σύστημά σας διαθέτει κάρτα γραφικών NVIDIA ή AMD.
	*Καθαρισμός NVIDIA Shader Cache: Προστέθηκε λειτουργία για αυτόματη διαγραφή φακέλων DXCache και GLCache (με το σύστημα try-except για αρχεία σε χρήση).
	*Υποστήριξη λογισμικού AMD: Προσθέστε ένα ειδικό κουμπί για να ανοίξετε το λογισμικό AMD και να εμφανίσετε οδηγίες για μη αυτόματη επαναφορά της προσωρινής μνήμης.
	*Νέο GUI.

## Ενημέρωση 12.01.2026
* RADIO MENU CREATOR 2 - DCS v.2.25
	* Προσθήκη κουμπιού "Load LUA file".
	* Υποστήριξη One-Liners: Μπορείτε να επικολλήσετε πολλές εντολές (c1, c2, c3...) στην ίδια ακριβώς γραμμή και το πρόγραμμα θα τις αναγνωρίσει όλες ξεχωριστά.
	* Space Tolerance: Αναγνωρίζει εντολές ακόμα κι αν υπάρχει κενό διάστημα πριν από την παρένθεση (π.χ. addCommand (...)) ή ανάμεσα στα κόμματα.
	* Αυτόματη διόρθωση ορφανών εντολών: Εάν μια εντολή αναφέρεται σε υπομενού που δεν υπάρχει (π.χ. sm1), το πρόγραμμα την αλλάζει αυτόματα σε μηδέν ώστε να εμφανίζεται κανονικά στη ΔΟΜΗ ΜΕΝΟΥ ΡΑΔΙΟΦΩΝΟΥ.
	* Υποστήριξη sm1/sm2: Δεν περιορίζεται πλέον σε συγκεκριμένα ονόματα (m1, m2). Διαβάζει οποιοδήποτε όνομα μεταβλητής χρησιμοποιείτε στον κωδικό LUA σας.
	* Βελτιωμένο TreeView: Οι εντολές "Orphaned" εμφανίζονται τώρα στην κορυφή του δέντρου αντί να εξαφανίζονται, ώστε να μπορείτε να τις επεξεργαστείτε αμέσως.
	
## Ενημέρωση 05.01.2026
* CLEAR TRASH - DCS v.1.16
	* Προστέθηκε αγγλική και ελληνική γλώσσα.
	* Προστέθηκε σκοτεινό και ανοιχτό θέμα.
* AstroSuite - DCS έκδοση 1.08
	* Προστέθηκε το GCI - DCS v.5.18 ένα script lua που προσομοιώνει την επίγεια ελεγχόμενη αναχαίτιση (GCI) για το DCS World Mission Editor.
* ΚΙΝΟΥΜΕΝΟΣ ΧΑΡΤΗΣ - DCS v.3.09
	* Αλλαγή διεπαφής εφαρμογής.
	* Προστέθηκε αγγλική και ελληνική γλώσσα.
	* Προστέθηκε σκοτεινό και ανοιχτό θέμα.
* DCS-PERSISTENCE v.2.04
	* Αλλαγή διεπαφής εφαρμογής.
* RADIO MENU CREATOR 2 - DCS v.2.24
	* Διορθώθηκε το πρόβλημα στην αποθήκευση αρχείου lua.
	* Προστέθηκε αγγλική και ελληνική γλώσσα.
	* Προστέθηκε σκοτεινό και ανοιχτό θέμα.

### Ενημέρωση 02.01.2026
* RADIO MENU CREATOR 2 - DCS v.2.19
	* Διορθώθηκε εάν δεν έχει κύριο μενού ή υπομενού για να εμφανίζεται σωστά ο κώδικας του radio menu.
	* Προστέθηκε η δυνατότητα επανάληψης/αναίρεσης έως και 10 φορές μπρος/πίσω.
		
### Περιγραφή
Το **AstroSuite - DCS** είναι μια ολοκληρωμένη σουίτα εργαλείων ανοιχτού κώδικα, σχεδιασμένη αποκλειστικά για τους πιλότους του **Digital Combat Simulator (DCS World)**. Σκοπός της είναι η βελτιστοποίηση της απόδοσης, η διαχείριση του αποθηκευτικού χώρου και η απλοποίηση της δημιουργίας αποστολών.

### 🛠️ Περιλαμβανόμενες Εφαρμογές

* **🧹 CLEAR TRASH - DCS:** Διαγράφει αυτόματα φακέλους προσωρινής αποθήκευσης (`fxo`, `metashaders2`), παλιά logs και tracks. Εξαλείφει τα stutters και διορθώνει οπτικά σφάλματα μετά από updates.
* **🗺️ MOVING MAP - DCS:** Διαχειριστής χώρου για τους χάρτες του DCS. Μεταφέρει τους ογκώδεις φακέλους σε άλλο δίσκο χρησιμοποιώντας **Symbolic Links (Symlinks)**, απελευθερώνοντας χώρο στον κεντρικό SSD.
* **💾 PERSISTENCE MANAGER - DCS:** Διαχειρίζεται το de-sanitization του αρχείου `MissionScripting.lua`. Επιτρέπει σε προηγμένα scripts αποστολών να αποθηκεύουν την πρόοδο της μάχης εξωτερικά.
* **🎙️ RADIO MENU CREATOR - DCS:** Εργαλείο για δημιουργούς αποστολών που επιτρέπει τη γρήγορη σχεδίαση μενού ασυρμάτου (F10 Menu) χωρίς χειροκίνητη συγγραφή κώδικα LUA.

### 🚀 Εγκατάσταση & Χρήση
1.  **Λήψη:** Κατεβάστε την τελευταία έκδοση από τα [Releases].
2.  **Δομή Φακέλων:** Τοποθετήστε τα `.exe` των εφαρμογών μέσα σε έναν υποφάκελο με όνομα `Applications`.
3.  **Δικαιώματα:** Εκτελέστε το `AstroSuite.exe` ως **Διαχειριστής** (Administrator) για τη σωστή λειτουργία των Symlinks και του καθαρισμού.


**ΠΡΟΕΙΔΟΠΟΙΗΣΗ: Η χρήση των εφαρμογών γίνεται με δική σας ευθύνη.**
---

## ⚖️ License & Copyright
AstroSuite - DCS v.1.09® 2025© for LOCK-ON GREECE by =GR= Astr0 with support Gemini AI

