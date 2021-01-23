# Awesome Minecraft [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome frameworks, libraries and software relating to Minecraft. All software listed must be open sourced
and available for free.

# Contents

- [Libraries and Frameworks](#libraries-and-frameworks)
  - [Commands](#commands)
  - [Configuration](#configuration)
  - [Messages](#messages)
  - [Utilities](#utilities)
- [Mods]
  - [Performance](#performance-mods)
- [Plugins](#plugins)
  - [Anti-Cheating](#anti-cheating)
  - [Building](#building)
  - [Other](#other)
    - [Bukkit](#bukkit)
    - [Sponge](#sponge)
    - [Velocity](#velocity)
  - [Permissions](#permissions)
  - [Region Management](#region-and-world-management)
- [Resources](#resources)
  - [Performance](#performance)
- [Software](#software)
  - [Proxy Software](#proxy-software)
  - [Server Software](#server-software)

# Libraries and Frameworks

## Commands
_Libraries that aid in the creation of Minecraft commands._

- [ACF](https://github.com/aikar/commands) - Annotation based Java Command Dispatch Framework.
- [Brigadier](https://github.com/Mojang/brigadier) - Brigadier is a command parser & dispatcher, designed and developed for Minecraft: Java Edition.
- [Cloud](https://github.com/Incendo/Cloud) - Command framework & dispatcher for the JVM with support for builders, annotations and a Kotlin DSL.
- [CommandAPI](https://github.com/JorelAli/CommandAPI) - A Bukkit-only API for the command UI introduced in Minecraft 1.13.
- [Commodore](https://github.com/lucko/commodore) - Utility for using Minecraft's 1.13 'brigadier' library in Bukkit plugins.

## Configuration
_Libraries that make it easier to work with configuration files._

- [Configurate](https://github.com/SpongePowered/Configurate/) - A simple configuration library for Java applications providing a node structure, a variety of formats, and tools for transformation.

## Messages
_Libraries that make it easier to work with messages, text, etc._

- [adventure](https://github.com/KyoriPowered/adventure) - A serverside user interface library for Minecraft: Java Edition.
- [adventure-text-minimessage](https://github.com/KyoriPowered/adventure-text-minimessage) - Simple library that implements an easy to use textual format to send rich json messages.
- [MineDown](https://github.com/Phoenix616/MineDown) - A MarkDown inspired markup library for Minecraft chat components.
- [PlaceholderAPI](https://github.com/PlaceholderAPI/PlaceholderAPI) - PlaceholderAPI is a plugin for Spigot servers that allows server owners to display information from various plugins with a uniform format.

## Utilities
_Utilities that don't particularly belong in any other category._

- [BKCommonLib](https://github.com/bergerhealer/BKCommonLib) - An extensive library used in bergerhealer's plugins.
- [helper](https://github.com/lucko/helper) - A collection of utilities and extended APIs to support the rapid and easy development of Bukkit plugins.
- [PacketWrapper](https://github.com/dmulloy2/PacketWrapper) - Packet wrapper classes for ProtocolLib.
- [ProtocolLib](https://github.com/dmulloy2/ProtocolLib/) - Provides read and write access to the Minecraft protocol with Bukkit.

# Mods

## Performance Mods
_Mods meant to increase game performance._

- [lazy-dfu](https://github.com/astei/lazydfu) - Makes Minecraft DataFixerUpper initializatiion lazy.
- [lithium-fabric](https://github.com/jellysquid3/lithium-fabric) - A Fabric mod designed to improve the general performance of Minecraft without breaking things.
- [phosphor-fabric](https://github.com/jellysquid3/phosphor-fabric) - A Fabric mod designed to dramatically improve the performance of Minecraft's lighting engine while fixing many bugs.
- [sodium-fabric](https://github.com/jellysquid3/sodium-fabric) - A Fabric mod designed to improve frame rates and reduce micro-stutter.

# Plugins

## Anti-Cheating

- [AACAdditionPro](https://github.com/Photon-GitHub/AACAdditionPro) - An anticheat with nieche checks to cover cheats usually not covered by anticheats.
- [NoCheatPlus](https://github.com/Updated-NoCheatPlus/NoCheatPlus) - NoCheatPlus attempts to enforce "vanilla Minecraft" mechanics, as well as preventing players from abusing weaknesses in Minecraft or its protocol, making your server more safe.

## Building
_Plugins that make building easier._

- [Builders-Utilities](https://github.com/Arcaniax-Development/Builders-Utilities) - A collection of a lot of tiny features that help with building.
- [Light-Cleaner](https://github.com/bergerhealer/Light-Cleaner) - Regenerates light levels in chunks or entire worlds to clean up dark spots. Continuation of NoLagg Lighting.
- [WorldEdit](https://github.com/enginehub/worldedit) - Minecraft map editor and mod.

## Other
_Plugins that don't particularly fit in with any existing category._

### Bukkit

- [Essentials](https://github.com/essentialsx/essentials) - The essential plugin suite for Bukkit servers.
- [ViaVersion](https://github.com/ViaVersion/ViaVersion) - Allows the connection of newer clients to older server versions for Minecraft servers.

### Sponge

- [Nucleus](https://github.com/NucleusPowered/Nucleus) - The Ultimate Essentials Plugin for Sponge.

### Velocity

- [Catalyst](https://github.com/AnvilPowered/Catalyst) - An essentials plugin for Minecraft proxies that will provide your server with a strong baseline; giving you all the useful commands you need.

## Permissions
_Plugins for user permission management._

- [LuckPerms](https://github.com/lucko/luckperms) - A permissions plugin for Minecraft servers.

## Region and World Management
_Plugins for managing and generating world regions._

- [Hyperverse](https://github.com/Incendo/Hyperverse) - A lightweight world mangement plugin for Bukkit.
- [Multiverse-Core](https://github.com/Multiverse/Multiverse-Core) - The original Bukkit Multi-World Plugin.
- [PlotSquared](https://github.com/IntellectualSites/PlotSquared) - Plot world generator and management plugin with support for schematics.
- [WorldGuard](https://github.com/enginehub/worldguard) - WorldGuard lets you and players guard areas of land against griefers and undesirables, as well as tweak and disable various gameplay features of Minecraft.

# Resources

## Blogs
_Blogs related to Minecraft._

- [Me4502](https://matthewmiller.dev/blog/) - Me4502's blog with frequent posts relating to Minecraft development and server ownership.

## Performance
_Resources for Minecraft performance tuning._

- [Aikar's Flags](https://aikar.co/2018/07/02/tuning-the-jvm-g1gc-garbage-collector-flags-for-minecraft/) - G1GC Garbage Collector Flags for Minecraft.

# Software

## Proxy Software
_Minecraft server proxy software._

- [Geyser](https://github.com/GeyserMC/Geyser) - A bridge/proxy allowing you to connect to Minecraft: Java Edition servers with Minecraft: Bedrock edition.
- [Velocity](https://github.com/velocitypowered/velocity) - A Minecraft server proxy with unparalleled server support, scalability, and flexibility.
- [Waterfall](https://github.com/papermc/waterfall) - BungeeCord fork that aims to improve performance and stability.

## Server Software
_Minecraft server software._

- [Nukkit](https://github.com/CloudburstMC/Nukkit) - Server software for Minecraft: Pocket Edition.
- [Paper](https://github.com/papermc/paper) - High performance Spigot fork that aims to fix gameplay and mechanics inconsistencies.
- [Purpur](https://github.com/pl3xgaming/Purpur) - Purpur is a fork of Paper and Tuinity with the goal of providing new and interesting configuration options, which allow for creating a unique gameplay experience not seen anywhere else.
- [Sponge](https://github.com/SpongePowered/Sponge) - A community-driven open source Minecraft: Java Edition modding platform.
- [Tuinity](https://github.com/spottedleaf/tuinity) - Fork of Paper aimed at improving server performance at high playercounts.