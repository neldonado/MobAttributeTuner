# MobAttributeTuner
https://i.hah.rip/MAT.png
A lightweight Minecraft plugin for **Paper 1.21.5** that allows you to customize mob attributes via a simple `config.yml` file.

🛠️ Built for: **Minecraft Java Edition 1.21.5**  
🔌 Server compatibility: **PaperMC (recommended)**

> ⚠️ This plugin relies on the Bukkit API — it may not work on non-Bukkit forks like Forge or Fabric.

---

## 📥 Installation

1. [Download the latest `.jar` here](https://github.com/neldonado/MobAttributeTuner/releases/tag/release)
2. Drop the compiled `MobAttributeTuner.jar` into your server's `plugins/` folder.
3. Start your server. A default `config.yml` will be generated.
4. Edit the `config.yml` to tweak mob behavior.

---

## ⚙️ Configuration

The `config.yml` includes a section for each mob. All mobs are commented out by default.

Uncomment the mobs you want to modify and set any of the following attributes:

```yaml
mobs:
  ZOMBIE:
    health: 20.0
    damage: 4.0
    armor: 2.0
    armor_toughness: 0.0
    knockback_resistance: 0.0
    movement_speed: 0.23




| Attribute              | Description                     | Bukkit Constant                |
| ---------------------- | ------------------------------- | ------------------------------ |
| `health`               | Max health of the mob           | `GENERIC_MAX_HEALTH`           |
| `damage`               | Melee attack damage             | `GENERIC_ATTACK_DAMAGE`        |
| `armor`                | Damage reduction value          | `GENERIC_ARMOR`                |
| `armor_toughness`      | Extra protection vs strong hits | `GENERIC_ARMOR_TOUGHNESS`      |
| `knockback_resistance` | Prevents knockback              | `GENERIC_KNOCKBACK_RESISTANCE` |
| `movement_speed`       | Movement speed (0.2 is normal)  | `GENERIC_MOVEMENT_SPEED`       |
