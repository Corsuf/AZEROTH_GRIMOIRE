# 📖 MyCharPanel — Azeroth Grimoire



<img width="2512" height="1288" alt="Снимок экрана от 2026-11-17 00-21-52" src="https://github.com/user-attachments/assets/a2577526-dcd6-4b59-bb5d-a82d449dbcfa" />

<img width="2512" height="1288" alt="Снимок экрана от 2026-11-17 00-28-28" src="https://github.com/user-attachments/assets/0f347ab3-de7a-44cc-a1c3-f2e7196a2c9a" />


<img width="2512" height="1288" alt="Снимок экрана от 2026-11-17 00-28-17" src="https://github.com/user-attachments/assets/0ac57d17-2423-46ce-8ef0-15c254e3c4ea" />




**A World of Warcraft Retail addon for character management, inventory tracking, and personal progression history.**

MyCharPanel Epic is a character management addon designed to bring your World of Warcraft characters, their equipment, inventory, bank contents, and progression history together in one convenient interface.

Originally developed for **World of Warcraft Retail 11.2.5**, the project aims to evolve alongside future game updates, with continued development and compatibility improvements for newer WoW versions.

The long-term goal is to build a comprehensive character archive — a personal grimoire documenting your journey through Azeroth.

---

## ✨ Features

### 👤 Character Overview
- Character archive with multiple characters.
- Character name, realm, class, race, and faction.
- Character level and specialization.
- Guild information.
- Equipped item level.
- Profession information and skill levels.
- Character gold balance.
- Total playtime and current-level playtime.
- Current login session duration.

### 🎒 Inventory & Bank Archive
- Automatic character inventory snapshots.
- Bank and reagent bank snapshots.
- Stored inventory data for previously recorded characters.
- Grid and list viewing modes.
- Item icons, stack counts, and quality-colored borders.
- Item tooltips.
- Separate inventory and bank archive windows.

### 📜 Character History
- Individual progression history for each character.
- Tracks changes in:
  - Character level.
  - Gold balance.
  - Equipped item level.
  - Specialization.
- Timestamped history entries.
- Configurable history storage limit.
- Review your character's progression over time.

### 📊 Account Statistics
- Combined overview of recorded characters.
- Total number of archived characters.
- Combined gold balance.
- Combined recorded playtime.
- Highest character level.
- Inventory and bank item counts.
- Total number of history records.

### 🎨 Interface & Customization
- Custom fantasy-inspired interface.
- Dark and Light parchment themes.
- Gold-colored borders and decorative elements.
- Optional glowing window borders.
- Optional decorative corners.
- Adjustable interface scale.
- Optional minimap button.
- Movable windows.
- Automatic settings and data persistence.

---

## 🎮 Slash Commands

Open the addon interface using the following commands:

| Command | Description |
|---|---|
| `/mcp` | Open the main character panel |
| `/mcp settings` | Open addon settings |
| `/mcp options` | Open addon settings |
| `/mcp stats` | View account statistics |
| `/mcp history` | View current character history |
| `/mcp refresh` | Refresh character data |

---

## 📥 Installation

1. Download the latest release from the [GitHub Releases](https://github.com/Corsuf/AZEROTH_GRIMOIRE/releases) page.
2. Extract the downloaded archive.
3. Place the `MyCharPanel` addon folder into your World of Warcraft AddOns directory.

Typical installation path:

`World of Warcraft/_retail_/Interface/AddOns/`

4. Restart the game or reload the interface.
5. Enable MyCharPanel Epic in the AddOns menu.
6. Enter the game and type `/mcp`.

---

## 🖥️ Compatibility

- **Game:** World of Warcraft Retail
- **Initial target version:** 11.2.5
- **Development direction:** Future Retail versions.

The addon is developed with future World of Warcraft updates in mind. As Blizzard changes the game's API and interface systems, compatibility updates and testing may be required.

Compatibility with newer game versions is a development goal and is not guaranteed until tested.

---

## 💾 Data Storage

MyCharPanel Epic uses WoW SavedVariables to store character information and addon settings locally.

Database name: `MyCharPanelDB`

Character records, inventory snapshots, bank snapshots, and progression history are stored between game sessions.

Historical records are collected from the moment the addon is installed and begins recording data. Previous progression cannot be reconstructed retroactively.

**Note:** The addon does not use an external database or cloud synchronization.

---

## 🚀 Development

MyCharPanel Epic is an evolving project.

Future development may include:
- Expanded character statistics.
- More detailed progression tracking.
- Additional character information.
- Improved inventory and bank management.
- Interface and usability improvements.
- Compatibility updates for future World of Warcraft Retail versions.

Suggestions, bug reports, and feature requests are welcome through the [Issues](https://github.com/Corsuf/AZEROTH_GRIMOIRE/issues) section.

---

## ❤️ Support the Project

If you enjoy using MyCharPanel Epic and appreciate the work behind its development, you can support the project through DonationAlerts.

[![Donate via DonationAlerts](https://img.shields.io/badge/Support%20the%20Project-DonationAlerts-orange?style=for-the-badge)](https://www.donationalerts.com/r/corsuf)

Every contribution is appreciated and helps support further development.

---

## 👨‍💻 Author

**Corsuf**

- GitHub: [@Corsuf](https://github.com/Corsuf)
- Project: [AZEROTH_GRIMOIRE](https://github.com/Corsuf/AZEROTH_GRIMOIRE)
- Donations: [DonationAlerts](https://www.donationalerts.com/r/corsuf)

---

*MyCharPanel Epic — Your characters. Your history. Your Azeroth.*
