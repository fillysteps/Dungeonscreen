# DungeonScreen

**A local editor and reference manager for Dungeons & Dragons 5th Edition (2014).**  
Developed by **Darkpilot** · Windows and Android

DungeonScreen brings homebrew creatures, magic items, spells, characters, encounters, quests, and notes into one organized workspace. Create entries, keep their details close at hand, and arrange the material for a session without making copies of everything you need. The application is designed to work alongside a virtual tabletop rather than replace it.

DungeonScreen keeps its campaign data on your device. It can be used offline, and projects can be transferred manually between Windows and Android.

## What you can create

- **Creatures:** Build 2014-style stat blocks with ability scores, traits, actions, spellcasting, and legendary or lair abilities. Artwork and formatted previews are optional.
- **Magic items:** Record equipment properties, magical effects, charges, curses, sentience, and other item details.
- **Spells:** Write casting details, school, components, effects, and higher-level descriptions. Spell schools have recognizable icons.
- **Characters:** Maintain character sheets with ability scores, skills, saving throws, combat statistics, features, spellcasting, personality details, and inventory. Inventory entries can be ordinary expandable notes or references to saved magic items, with quantities, equipment state, and attunement.
- **Encounters:** Assemble creatures from the library and preserve each combatant's HP, temporary HP, AC, conditions, saving throws, resources, bonuses, and notes. Instance changes are kept separate from the source stat block.
- **Quests:** Track where a quest began, its progression, status, rewards, and additional notes.
- **Notes:** Keep freeform writing with optional, rearrangeable titled sections.

The Editor and Preview work together: selecting text in a formatted preview locates the corresponding field in the editor. Available appearance options include themes, entry colors, font choices, and compact or classic stat-block layouts.

## Campaigns, Entries, and Projects

A **Campaign** is the main folder holding your saved material. Entries are the original creature sheets, items, spells, characters, encounters, quests, and notes within it.

The **Entry Library** keeps those documents separated by type. Use the search bar, tags, folders, and sorting controls to locate material quickly. Folder and entry options are available through the `•••` menu or by right-clicking on desktop. Entries can be renamed, cloned, labeled, and organized without changing their underlying type.

**Projects** are flexible workspaces inside a Campaign. A Project can bring together references to any combination of entry types: for example, the creatures, loot, quests, and notes prepared for a particular session. Adding an entry to a Project doesn't move or duplicate the original. Changes to the original are available wherever the entry is referenced.

Folders and Projects can have their own colors, tags, and thumbnails. On desktop, drag entries toward a valid folder drop zone to move or organize them; release outside a valid destination to cancel. Multiple entries can be selected using Ctrl or Shift, and there are menu-based Move commands as an alternative. On Android, use the touch-friendly menus for organization.

## Getting started

### Windows

1. Download the Windows release and extract the archive if necessary.
2. Run **`DungeonScreen.exe`**.
3. Create a Campaign, or choose an existing DungeonScreen or D&D 5e Forge campaign folder.

The Windows edition uses Edge or Chrome to display its local interface. The Editor and Preview can be detached into separate resizable windows. Some Windows systems may show a security warning for the unsigned executable; only install software obtained from a source you trust.

### Android

1. Obtain **`DungeonScreen.apk`** from an Android release, if one has been provided. Open it from the device's Files app and follow the installation prompts.
2. Launch DungeonScreen and select or create a Campaign folder through Android's system file picker.
3. Use the **Library**, **Editor**, and **Preview** navigation tabs to work with your entries.

The Android interface is optimized for touch. Desktop-specific functions such as detachable windows are not included. If a release supplies **Android source/build files rather than an APK**, follow the build instructions included with that package.

## Saving, transfers, and backups

Campaigns are ordinary directories containing entry JSON files, artwork, revisions, and organization metadata. The main manifest retains its original filename, `forge.project.json`, for compatibility with existing Forge projects. The additional `dungeonscreen.library.json` file preserves folders, Projects, labels, and entry references.

To move a Campaign between devices, **copy the entire Campaign folder**, not individual entry files. Include the artwork, both metadata files, and all category folders. Project ZIP import/export provides an alternative transfer method where supported.

Windows and Android editions built for the same project schema are intended to read these files directly. Transfers are manual; there is no automatic synchronization or conflict resolution. Back up important Campaigns before upgrading or moving them, and avoid modifying separate copies at the same time.

## Help and documentation

Open **☰ Menu → About** from the main Project Manager for the built-in guide. It explains creating and organizing entries, Projects, character inventory, encounter management, search, revisions, themes, and other features in more detail.

**Developer:** Darkpilot  
**Questions and support:** Please forward questions and concerns to the project's current maintainer by email at **fillynatarashi@gmail.com**.
