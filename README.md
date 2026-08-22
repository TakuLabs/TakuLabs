<h1 align="center">TakuLabs</h1>
<h3 align="center">Java & Minecraft Plugin Development</h3>

<p align="center">
  Building Java-based Minecraft plugins and focused server systems with attention to maintainable architecture, inventory workflows, persistence and gameplay features.
</p>

<p align="center">
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio#technologies"><img src="https://img.shields.io/badge/Java-21-2f3437?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21"></a>
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio#technologies"><img src="https://img.shields.io/badge/Paper-1.21.x-2f3437?style=flat-square" alt="Paper 1.21.x"></a>
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio#technologies"><img src="https://img.shields.io/badge/Maven-Build-2f3437?style=flat-square&logo=apachemaven&logoColor=white" alt="Maven"></a>
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio#featured-project"><img src="https://img.shields.io/badge/Minecraft-Plugins-2f3437?style=flat-square" alt="Minecraft Plugins"></a>
</p>

---

## Featured Work

### [Minecraft Plugin Portfolio](https://github.com/TakuLabs/minecraft-plugin-portfolio)

A curated Java/Paper plugin portfolio with standalone projects, selected examples and extracted systems from larger private server work.

### [EmpireCrates](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates)

Crate-system module originally developed as part of a larger private server core, then extracted and prepared as a focused public showcase.

<p align="center">
  <a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates">
    <img src="https://raw.githubusercontent.com/TakuLabs/minecraft-plugin-portfolio/main/assets/empirecrates/crate-showcase.gif" alt="EmpireCrates in-game crate showcase" width="760">
  </a>
</p>

<p align="center"><sub>In-game crate showcase and opening system</sub></p>

`Java 21 · Paper · Maven · PlaceholderAPI · YAML`

- Inventory administration GUI and chat-based editing flow
- YAML-backed crate, key and reward configuration
- Reward rarity/chance handling and persistent player progress
- Physical key validation using Bukkit PersistentDataContainer
- Opening animations with particles and sounds

[View EmpireCrates](https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/EmpireCrates) · [View portfolio](https://github.com/TakuLabs/minecraft-plugin-portfolio)

---

## Development Focus

- Modular Paper/Bukkit plugin architecture
- Inventory GUI workflows
- Configuration-driven systems
- Persistent plugin state
- Event-driven gameplay features
- Optional API integrations where useful

## Tech Stack

**Core:** `Java 21` · `Paper API` · `Bukkit API` · `Maven` · `YAML`

**Selected integrations:** `Vault` · `PlaceholderAPI` · `ProtocolLib` · `ModelEngine`

## Selected Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/SMPShop">SMPShop</a></h3>
      <p>Server-controlled economy shop with category menus, buy/sell pricing and quantity selection.</p>
      <p><code>Java 21 · Paper · Maven · Vault · YAML</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/NovaGuard">NovaGuard</a></h3>
      <p>Connection and packet safeguard plugin with whitelist, blacklist and packet-rate handling.</p>
      <p><code>Java 21 · Paper · Maven · ProtocolLib · JUnit</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/BirthdayEvent">BirthdayEvent</a></h3>
      <p>Small event plugin for a configured birthday event window.</p>
      <p><code>Java 21 · Paper · Maven · JUnit</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/TakuLabs/minecraft-plugin-portfolio/tree/main/plugins/OtakuAuctionHouse">OtakuAuctionHouse</a></h3>
      <p>Auction house plugin for player-to-player item listings and purchases.</p>
      <p><code>Java 21 · Paper · Maven · Vault · YAML</code></p>
    </td>
  </tr>
</table>

## Private Core Context

Some showcased systems were extracted from larger private server projects so their architecture and implementation can be reviewed without publishing the complete private codebase.

## About

I build Java-based Minecraft server plugins and focused server systems. This profile links to the public portfolio where the code, documentation and selected examples can be reviewed.
