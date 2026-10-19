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
