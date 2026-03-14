# LITFlavor — Lithuanian Flavor Mod for EU5

A mod for **Europa Universalis V** that extends Lithuanian flavor through historically grounded events, journal entries, and cultural mechanics for the **Grand Duchy of Lithuania**.

## Features

### Flavor Events
Ten handcrafted events covering key moments in Lithuanian history:

| Event | Description |
|-------|-------------|
| The Legacy of Mindaugas | Lithuania's only crowned king and his ambiguous Christian legacy |
| The Christianization of Lithuania | Europe's last pagan state joins the Christian world |
| Vytautas the Great | Lithuania's greatest ruler expands the realm from Baltic to Black Sea |
| The Battle of Grunwald | The decisive victory that broke the Teutonic Order |
| The Statute of Lithuania | One of Europe's most advanced legal codes |
| The Baltic Amber Trade | Mastering the ancient amber routes that link North to South |
| The Iron Wolf of Vilnius | The founding legend of the Lithuanian capital |
| The Ruthenian Nobles | Integrating Orthodox boyars into the Lithuanian state |
| The Reformation in Lithuania | Navigating Protestant pressures and Counter-Reformation |
| The Dream of Gediminas | The legendary omen that foretold the founding of Vilnius |

### Journal Entries
Four guided journal entries with multi-step objectives:

- **The Grand Duchy Ascendant** — Expand the realm, secure the Baltic coast, and crush the Teutonic Order
- **The Old Ways and the New Faith** — Navigate Lithuania's transition from paganism to Christianity
- **The Lithuanian Statute** — Build a codified legal system and develop the realm's cities
- **The Amber Roads** — Dominate the Baltic amber trade and fill the treasury

## Mod Structure

```
LITFlavor/
├── .metadata/
│   └── metadata.json          # Mod descriptor for the EU5 launcher
├── in_game/
│   ├── events/
│   │   └── lit_flavor_events.txt      # All Lithuanian flavor events
│   ├── common/
│   │   └── journal_entries/
│   │       └── lit_journal_entries.txt # Journal entries / objectives
│   └── localization/
│       └── english/
│           └── lit_flavor_l_english.yml # English localization
├── loading_screen/
├── main_menu/
└── README.md
```

## Installation

1. Download or clone this repository.
2. Copy the `LITFlavor` folder into your EU5 mod directory:
   - **Windows:** `%USERPROFILE%\Documents\Paradox Interactive\Europa Universalis V\mod\`
   - **Linux:** `~/.local/share/Paradox Interactive/Europa Universalis V/mod/`
   - **macOS:** `~/Documents/Paradox Interactive/Europa Universalis V/mod/`
3. Launch EU5 and enable **LITFlavor - Lithuanian Flavor** in the mod manager.
4. Start a new game as Lithuania (`LIT`) to experience the new flavor content.

## Compatibility

- **Game Version:** EU5 1.0.*
- **Compatible with:** Most content mods that do not replace `events/` or `common/journal_entries/`
- **Not compatible with:** Total conversion mods or mods that fully override Lithuanian event files

## Contributing

Contributions are welcome! Feel free to open issues or pull requests to:
- Add new historical events covering other aspects of Lithuanian history
- Improve event descriptions and historical accuracy
- Add localization for other languages
- Expand journal entries with more objectives

## License

This mod is open source. See the repository for details.
