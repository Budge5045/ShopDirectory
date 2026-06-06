# 🏪 ShopDirectory

**Advanced Shop Search & Teleport GUI for Paper 1.21+**

ShopDirectory is a powerful GUI-based marketplace browser for Minecraft servers using Shopkeepers and QuickShop. Players can browse items being sold across the server, view all sellers offering an item, and teleport directly to the shop they want to visit.

Built for performance, stability, and ease of use.

---

## ✨ Features

* 🔍 Browse all items currently being sold with `/shops`
* 🧭 Click an item to view all sellers offering it
* 👤 View sellers through an intuitive GUI
* 🚀 Teleport directly to a selected shop
* 📦 Supports `/shops <item>` for quick item lookups
* 🔄 Automatic market indexing refresh
* ⚡ Optimized for performance and large economies
* 🪙 Supports custom currencies including emeralds, diamonds, blocks, and more
* 🎨 Fully customizable messages through `messages.yml`
* 🧠 Smart item indexing and seller tracking
* 🏪 Supports both Shopkeepers and QuickShop
* 📖 Built-in help and version commands

---

## 📦 Requirements

* Paper 1.21+
* Java 21+
* Shopkeepers 2.25.0+ and/or QuickShop

---

## 📜 Commands

| Command          | Description                      |
| ---------------- | -------------------------------- |
| `/shops`         | Open the item browser            |
| `/shops <item>`  | Open sellers for a specific item |
| `/shops help`    | View available commands          |
| `/shops version` | View plugin version              |
| `/shops reload`  | Refresh the market index (Admin) |

### Aliases

| Alias            |
| ---------------- |
| `/shopdirectory` |

Examples:

```text
/shops
/shops diamond
/shops help
/shopdirectory version
```

---

## ⚙️ Configuration

### config.yml

```yaml
auto-refresh-seconds: 300
```

The market index will automatically refresh every 300 seconds (5 minutes).

---

## 🛠 Installation

1. Install Shopkeepers and/or QuickShop.
2. Download the latest ShopDirectory release.
3. Place the JAR into your `/plugins` folder.
4. Restart the server.
5. Create shops using your preferred shop plugin.
6. Run `/shops` to begin browsing.

---

## 🔧 Compatibility

* Paper 1.21+
* Shopkeepers
* QuickShop
* Java 21+

---

## 📞 Support

Need help or found a bug?

**Email:** [buzzle435@gmail.com](mailto:buzzle435@gmail.com)

Please include:

* Server version
* Plugin version
* Error logs (if applicable)
* Steps to reproduce the issue

---

## 📄 License

Copyright © 2026 Buzzle's Hive

All Rights Reserved.
