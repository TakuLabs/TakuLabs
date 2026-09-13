<p align="center">
  <img src="assets/profile/hero.svg" alt="TakuLabs - Java Backend and Minecraft Systems" width="100%">
</p>

<p align="center">
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio"><b>Portfolio</b></a>
  ·
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates"><b>EmpireCrates</b></a>
  ·
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/MythicSpawner"><b>MythicSpawner</b></a>
  ·
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/docs/case-studies"><b>Engineering Notes</b></a>
</p>

<p align="center">
  <code>Java 21</code>
  <code>Paper</code>
  <code>Maven</code>
  <code>JDBC</code>
  <code>JDA</code>
  <code>ProtocolLib</code>
</p>

<p align="center">
  <img src="assets/profile/divider.svg" alt="" width="100%">
</p>

## Development Focus

I build Java-based Minecraft server systems, backend integrations and supporting tooling. Most of my public work centers on Paper plugins, inventory workflows, economy systems and small service layers extracted from real server projects.

I care about code that is easy to trace: clear boundaries, configuration-driven behavior, focused persistence and tests where they make the system easier to trust.

## Featured Work

### [EmpireCrates](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates)

Configurable Paper crate system with admin tooling, reward management, persistent player progress and optional server API integrations.

<p align="center">
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates">
    <img src="https://raw.githubusercontent.com/TakuLabs/minecraft-plugin-portfolio/main/assets/empirecrates/crate-showcase.gif" alt="EmpireCrates in-game crate showcase" width="820">
  </a>
</p>

<p align="center"><sub>In-game crate showcase and opening system</sub></p>

- Inventory-based admin GUI and editing flow
- Reward rarity, chance and command/item handling
- Physical key validation through Bukkit `PersistentDataContainer`
- Persistent crate state and player milestone progress

### [MythicSpawner](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/MythicSpawner)

Documentation-only showcase for custom spawner tooling.

- Custom spawner pickaxe and converted spawner flow
- Item and block state through Bukkit `PersistentDataContainer`
- Paginated mob-selection GUI
- Compatibility checks for virtual spawner plugins

### [Discord / Minecraft Platform](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/docs/case-studies/discord-minecraft-platform.md)

Architecture note for a private multi-module platform connecting a Paper plugin, Discord bot, database layer and web backend.

- Java service modules shared across adapters
- JDA-based Discord integration
- JDBC repository boundary
- Paper plugin bootstrap and account-linking flow

## More Projects

| Project | Focus |
| --- | --- |
| [SMPShop](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/SMPShop) | Economy shop and GUI flows |
| [NovaGuard](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/NovaGuard) | Connection and packet safeguards |
| [OtakuAuctionHouse](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/OtakuAuctionHouse) | Player marketplace |
| [BirthdayEvent](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/BirthdayEvent) | Restart-safe timed event logic |

## Engineering Notes

- [SellChest Performance](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/docs/case-studies/sellchest-performance.md)
- [Container Optimization](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/docs/case-studies/container-optimization.md)
- [Bounty Abuse Prevention](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/docs/case-studies/bounty-abuse-prevention.md)

## Technical Stack

`Java 21` · `Maven` · `Paper API` · `Bukkit API` · `YAML` · `Vault` · `PlayerPoints` · `PlaceholderAPI` · `ProtocolLib` · `ModelEngine` · `JDA` · `JDBC` · `JUnit`

## Private Core Context

Some systems come from larger private server projects. Public showcases focus on architecture and selected implementation details without publishing private infrastructure or complete server codebases.

## Links

- [Full portfolio](https://github.com/TakuLabs/minecraft-plugin-portfolio)
- [GitHub profile](https://github.com/TakuLabs)
