# Built-in features for lingua-loop-os

Purpose: language learning

1. **prepare study and research files** — run lingua-loop-os-workspace. It creates ~/Documents/lingua-loop-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run lingua-loop-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/lingua-loop-os-session-plans/.
3. **check study and source readiness** — run lingua-loop-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/lingua-loop-os-workspace features/lingua-loop-os-plan features/lingua-loop-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for language learning:

1. **Zotero** — org.zotero.Zotero
2. **Foliate** — com.github.johnfactotum.Foliate
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for language learning:

1. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
2. **Thonny** — write and debug Python code (org.thonny.Thonny)
3. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
4. **QGIS** — analyze geographic data and make maps (org.qgis.qgis)
5. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
8. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
9. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
10. **GNOME Weather** — check local weather conditions (org.gnome.Weather)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
2. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
3. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
4. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
5. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
6. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
7. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
8. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
9. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
10. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
11. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
12. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
13. **Document Scanner** (org.gnome.SimpleScan) — digitize paper notes and forms.
14. **GNOME Boxes** (org.gnome.Boxes) — test workflows in virtual machines.
15. **GNOME Text Editor** (org.gnome.TextEditor) — edit plain-text notes and configuration files.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
