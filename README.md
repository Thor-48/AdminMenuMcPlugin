# Admin Menu

Admin Menu is a powerful and easy-to-use Minecraft administration plugin designed to make player moderation faster and more convenient through a graphical interface.

## Features

* **Admin Mode** — Enable or disable Admin Mode with `/admin`.
* **Player Management** — Shift + Right-Click a player with an empty main hand to open the Admin Menu.
* **Kick** — Instantly kick the selected player.
* **Kill** — Instantly kill the selected player.
* **Invsee** — Open the selected player's inventory using the configured `/invsee <player>` command.
* **Temporary Bans** — Choose from multiple predefined ban durations.
* **Permanent Bans** — Permanently ban players with either a normal ban or an IP ban.
* **Ban Confirmation** — Confirm bans before they are executed to prevent accidental actions.
* **Permission Support** — Admin Mode and all menu features are protected by a dedicated permission.
* **Automatic Cleanup** — Temporary player selections and admin data are automatically cleared when necessary.

## Commands

### `/admin`

Toggles Admin Mode on or off.

When Admin Mode is enabled, Shift + Right-Click another player while holding nothing in your main hand to open the Admin Menu.

**Permission:** `adminmenu.use`
**Default:** OP

## Admin Menu

### Kick

Kicks the selected player from the server.

### Kill

Instantly kills the selected player.

### Invsee

Runs the configured `invsee <player>` command using the selected player's real Minecraft username.

### Ban

Opens the ban management menu.

Available temporary ban durations:

* 1 Minute
* 5 Minutes
* 10 Minutes
* 30 Minutes
* 1 Hour
* 6 Hours
* 12 Hours
* 1 Day
* 7 Days
* 90 Days

Permanent bans can be configured as:

* **Normal Ban**
* **IP Ban**

Every ban includes a confirmation screen before execution.

## Permissions

| Permission      | Description                                             | Default |
| --------------- | ------------------------------------------------------- | ------- |
| `adminmenu.use` | Allows the player to use Admin Mode and the Admin Menu. | OP      |

## Requirements

* Minecraft **1.21+**
* Bukkit, Spigot, or Paper
* Permission `adminmenu.use`

## Support & Community

[**DC Server for Custom Plugins**](https://discord.gg/D8DtJF2Jye)

## License

Admin Menu is licensed under the **Admin Menu License**.

You may use, modify, and redistribute the plugin, including on commercial servers. However, the original plugin and modified versions may **not be sold**.

[**View the full Admin Menu License**](https://github.com/Thor-48/AdminMenuMcPlugin/blob/main/LICENSE.md)
