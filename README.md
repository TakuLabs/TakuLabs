<p align="center">
  <img src="assets/profile/hero.svg" alt="TakuLabs - Minecraft Systems and Backend Development" width="100%">
</p>

<p align="center">
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio"><b>Portfolio</b></a>
  ·
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates"><b>EmpireCrates</b></a>
  ·
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/SMPShop"><b>SMPShop</b></a>
  ·
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/NovaGuard"><b>NovaGuard</b></a>
</p>

<p align="center">
  <code>Java 21</code>
  <code>Paper API</code>
  <code>Bukkit API</code>
  <code>Maven</code>
  <code>YAML</code>
  <code>Vault</code>
  <code>PlaceholderAPI</code>
  <code>ProtocolLib</code>
  <code>ModelEngine</code>
</p>

<p align="center">
  <img src="assets/profile/divider.svg" alt="" width="100%">
</p>

## Development Focus

TakuLabs is a small development lab for Java-based Minecraft server systems, backend-oriented plugin architecture and focused gameplay infrastructure. The public portfolio is built to show practical code structure, maintainable Paper API usage and selected systems extracted from larger private server work.

| Area | Focus |
| --- | --- |
| Minecraft server systems | Paper/Bukkit plugins, event-driven features, inventory workflows |
| Backend architecture | Service layers, persistence boundaries, configuration-driven behavior |
| Security tooling | Connection limits, packet-rate handling, whitelist and blacklist flows |
| Economy and gameplay | Crates, shops, auctions, rewards and player-facing GUI systems |
| Developer tooling | Maven builds, clean project layouts, tests where they add confidence |

## Flagship Project

### [EmpireCrates](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates)

EmpireCrates is the main public showcase: a configurable Paper crate system with admin tooling, reward management, persistent player progress and optional server API integrations.

<p align="center">
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates">
    <img src="https://raw.githubusercontent.com/TakuLabs/minecraft-plugin-portfolio/main/assets/empirecrates/crate-showcase.gif" alt="EmpireCrates in-game crate showcase" width="820">
  </a>
</p>

<p align="center"><sub>In-game crate showcase and opening system</sub></p>

`Java 21` · `Paper` · `Maven` · `PlaceholderAPI` · `ModelEngine` · `YAML`

- Inventory-based admin GUI with focused editing flows
- Reward rarity and chance handling with configurable rewards
- Persistent player progress and crate state
- Physical key validation through Bukkit `PersistentDataContainer`
- Keyall support and optional placeholder-driven presentation

[View source](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates) · [View full portfolio](https://github.com/TakuLabs/minecraft-plugin-portfolio)

<p align="center">
  <img src="assets/profile/divider.svg" alt="" width="100%">
</p>

## Selected Systems

### [SMPShop](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/SMPShop)

GUI shop system for SMP-style servers with categories, pagination, economy integration and configurable buy/sell behavior.

`Java 21` · `Paper` · `Maven` · `Vault` · `YAML`

- Category-based inventory menus
- Buy and sell flows with quantity selection
- Configurable assortment and reload handling
- Economy integration through Vault

### [NovaGuard](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/NovaGuard)

Security and infrastructure showcase for connection handling, packet-rate limiting and defensive server workflows.

`Java 21` · `Paper` · `Maven` · `ProtocolLib` · `JUnit`

- IP account limits and connection checks
- Whitelist and blacklist service structure
- ProtocolLib-backed packet-rate handling
- Tests around core guard behavior

### [OtakuAuctionHouse](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/OtakuAuctionHouse)

Public preview of a larger auction ecosystem currently being redesigned, focused on player item listings and purchase flows.

`Java 21` · `Paper` · `Maven` · `Vault` · `YAML`

- Player-to-player item listings
- Economy-backed purchase flow
- Inventory-based browsing experience
- Standalone preview structure for portfolio review

### [BirthdayEvent](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/BirthdayEvent)

Event and scheduler example for restart-safe timed gameplay states with configurable date and timezone logic.

`Java 21` · `Paper` · `Maven` · `JUnit`

- Persistent event state handling
- Restart-safe scheduling behavior
- Configurable event windows
- Focused tests for date-related logic

## Technical Stack

| Layer | Technologies |
| --- | --- |
| Language and build | `Java 21`, `Maven`, `Git` |
| Minecraft platform | `Paper API`, `Bukkit API` |
| Configuration | `YAML`, plugin-specific config models |
| Integrations | `Vault`, `PlayerPoints`, `PlaceholderAPI`, `ProtocolLib`, `ModelEngine` |
| Testing | `JUnit`, focused service-level tests |

## Private Core Context

Some showcased systems were extracted from larger private server projects so their architecture can be reviewed without publishing the complete private codebase. The portfolio keeps public examples small, standalone and free of private server infrastructure.
