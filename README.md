# 🏪 ShopDirectory
### Advanced Shopkeepers Item Search & Teleport GUI for Paper 1.21.x

ShopDirectory is a powerful GUI-based marketplace index for Minecraft servers using **Shopkeepers**.  
It allows players to browse all items being sold and teleport directly to the shop selling them.

Built for performance, stability, and clean user experience.

---

## ✨ Features

- 🔍 `/shops` opens a GUI of all items currently sold by Shopkeepers
- 🧭 Click an item to view all sellers offering that item
- 👤 Seller GUI shows player skulls of shop owners
- 🚀 Click a seller skull to teleport directly to that shop
- 📦 Supports `/shops <item>` to directly open sellers for that item
- 🔄 Automatic indexing refresh (configurable)
- ⚡ Optimized for performance (safe indexing — no deep reflection scans)
- 🪙 Supports custom currencies (emeralds, diamonds, blocks, etc.)
- 🎨 Fully customizable messages via `messages.yml`
- 🧠 Smart indexing by material type

---

## 📦 Requirements

- **Paper 1.21.x**
- **Shopkeepers 2.25.0+**
- Java 21 recommended

---

## 📜 Commands

| Command | Description |
|----------|-------------|
| `/shops` | Opens item browser GUI |
| `/shops <item>` | Opens seller list for specific item |
| `/shops reload` | Reloads configuration (OP only) |

---

## 🛠 Installation

1. Install Shopkeepers.
2. Place `ShopDirectory.jar` into your `/plugins` folder.
3. Restart your server.
4. Ensure Shopkeepers shops exist.
5. Use `/shops` to open the GUI.

---

## ⚙ Configuration

`config.yml`
```yaml
auto-refresh-seconds: 300

For Support, please contact us. 
Email: buzzle435@gmail.com

/*
 * Buzzle’s Hive Plugin
 * Copyright (c) 2026
 * All Rights Reserved.
 *
 * Unauthorized copying or distribution of this file is strictly prohibited.
 */