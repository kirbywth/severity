# Severity

A free, original launcher for **Minecraft: Java Edition**, with its own in-game client for Fabric.

Severity is an independent project. It is not affiliated with, endorsed by, or connected to Mojang Studios or Microsoft. "Minecraft" is a trademark of Mojang Studios.

## What it does

**Launcher (desktop app)**
- Separate game profiles with their own settings, Java path and memory
- Launches Vanilla and Fabric profiles
- Mod, resource pack and shader browser using the Modrinth API. Downloads are checked against Modrinth's published file hashes
- Saved server list with one-click join (Minecraft 1.20 and newer)

**In-game client (Fabric mod)**
- In-game menu with searchable modules, settings, keybinds and configuration profiles
- Drag-and-drop HUD editor
- FPS, coordinates and memory displays, and zoom

## Fair play

Severity is not a cheat client. It has no combat aids, reach changes, or anything that bypasses security, authentication or license checks.

## Sign-in and privacy

- Players sign in with their Microsoft account through the standard OAuth flow in their normal web browser. Severity never sees or asks for a password and uses no client secret.
- It then uses Xbox Live and the official Minecraft services to confirm the account owns Minecraft: Java Edition.
- Refresh tokens are stored encrypted using the operating system's keystore. Access tokens stay in memory only. Tokens are never written to logs.
- Severity only starts the game for accounts that own it.

## Status

Early development. Some features are not built yet, including skins and cosmetics, favorites, and server status pings.

## Contact

Open an issue on this repository.
