# ⚡ Shortcut Cheat Sheet

A compact collection of useful shortcuts, tips, and workflows for daily production.

---

## 🧭 Quick Navigation

- [Blender](#-blender)
- [Plasticity](#-plasticity)
- [Substance Painter](#-substance-painter)
- [DaVinci Resolve](#-davinci-resolve)
- [ComfyUI](#-comfyui)
- [Windows](#-windows)
- [MacOS](#-macos)
- [Command Line (CMD & PowerShell)](#-command-line-cmd--powershell)
- [Notepad++](#-notepad)
- [VScode](#-vscode)
- [General Tips](#-general-tips)

---

## 🟠 Blender

### General

- **Alt + Q** — Switch between shapes
  *(Press in weight paint mode or in edit mode to switch between shapes. Press ALT hover over another mesh and press Q)*

- **Shift + R** — Repeat last operation

- **Ctrl + Shift + R** — Korean Bevel  
  *(Creates two proportional loop cuts around an edge)*

- **Ctrl + Space** — Fullscreen current editor

- **Window → New Window** — Open a separate render window that stays on top

### Animation & Graph Editor

- **Alt + D** — Open interpolation menu (Graph Editor)
- **Shift + E** — Set in-between pose (animation)

### Modeling

- **Ctrl + E → H** — Clear Sharp edges
- **Ctrl + H** — Hook to object
- **Select edge/vert + V** — disconnect edge/vert

### Object / Pose Mode

- **Ctrl + Alt + C** — Copy attribute (Object / Pose) (This is a custom shortcut I use to preserve Ctrl + C for standard copy, while still being able to use the Copy Attributes Menu add-on. Since the add-on uses the same shortcut by default, I reassigned it to Ctrl + Alt + C.)

### UV Editor

- **Ctrl + B** — Create custom packing region  
- **Ctrl + Alt + B** — Clear custom packing region

### Node Wrangler

- **Alt + S** — Switch texture channels
- **Ctrl + Shift + Click** — Preview node output

### Skin Modifier

- **Ctrl + A** — Adjust skin radius scale
- **Alt + S** — Smooth skin result

### Blender Baking Tip

To bake from high-poly to low-poly with different UVs:

- Bake: **Diffuse**
- Disable **Direct** and **Indirect**
- Enable **Selected to Active**
- Set **Metallic = 0** on source material

Metallic values above zero may cause very dark textures.

### Blender MacOS location Tip

in finder press **CMD + SHIFT + G** in following window paste this `~/Library/Application Support/Blender/5.0(or your version)/config`

that is a config folder that contain all blender configurations. This folder can be saved as a backup

### Blender Batch Rename Win\MacOS Tip

select your objects\bones\ets in the Outliner, Posemode or 3D Viewport, then press **Ctrl + F2(WIN)/CMD + F2** (or go to `Edit > Batch Rename`)

---

## 🔵 Plasticity

- **J** — Join
- **F** — Quick menu (similar to Shift + A in Blender)
- **Shift + J** — Patch (creates surface from selected curves)

### Selection

- **1 / 2 / 3 / 4** — Selection modes
- **Ctrl + 1 / 2 / 3 / 4** — Convert selection

### Boolean & View

- **Q** — Boolean operation (cycle Join / Cut / Intersect)
- **.** — Isolate mode
- **/** — Focus view

### Modeling

- **Ctrl + R** — Loop cut  
  - **Tab** — Switch direction  
  - **Shift + Scroll** — Change cut count

---

## 🟢 Substance Painter

- **Alt + Shift + drag LMB** — Align camera view 
- **Ctrl + move right\left RMB** — Brush size
- **Ctrl + move up\down RMB** — Brush hardness
- **Ctrl + move right\left LMB** — Brush flow
- **Ctrl + move up\down LMB** — Brush rotation
- **Shift + move up\down RMB** — HDRI rotation
- **Shift + move up\down LMB** — Draw straight line
---

## 🟣 DaVinci Resolve

- **Alt + Y** — Select all clips after playhead
- **Ctrl + Y** — Select all clips before playhead
- **Ctrl + Shift + <** — Move clip left and swap
- **Ctrl + Shift + >** — Move clip right and swap
- **(clip shoul be deselected in UI) Alt + left click + move** — Duplicate only selected part of linked clip

---

## 🟢 ComfyUI

- **Ctrl + Enter** — Queue prompt
- **Shift + Enter** — Queue without clearing
- **Ctrl + .** — Stop processing
- **Ctrl + 0** — Reset zoom

---

## 🪟 Windows

- **Win + .** — Emoji & symbols panel
- **Ctrl + Win + T** — Always on top
- **Win + Ctrl + Caps Lock** — Enable zoom
- **Win + Ctrl + Tab** — Draw / sketch mode
- **Win + Ctrl + S** — Screen shot
- **PRNT** — Screen shot

---

## 🍏 MacOS

- **Fn + E** — Emoji & symbols panel

---

## 💻 Command Line (CMD & PowerShell)

### CMD

```bat
- **cd** — Verify disk
- **cd C:\Users\username\Desktop\temp_SSD_blends** — go to the folder in the same directory
- **cd /d C:\Users\username\Desktop\temp_SSD_blends** — go to the folder in new directory (/d - change directory)
- **cd /d %USERPROFILE%** — back to default directory
- **mkdir TestFolder** — new folder named "TestFolder"
```

### PowerShell

```powershell
- **Get-Location** — Verify disk
- **cd "C:\Users\username\Desktop\temp_SSD_blends"** — go to the folder (do not need /d to change directory but need "" around the path)
- **cd ~** — back to default directory
- **mkdir TestFolder** — new folder named "TestFolder"
```

### Linux (Bash – generic)

```linux
- **pwd** — verify current directory
- **cd ~/Desktop/temp_SSD_blends** — go to the folder ( "~" — is here for /home/username)
- **cd ~** — back to home directory
- **ls ~** — list files in home directory
- **ls -lah** — detailed list (including hidden)
- **mkdir TestFolder** — create a new folder named "TestFolder"
```

### WSL (Windows Subsystem for Linux)

- **wsl --shutdown** — completely shut down all running WSL distributions
- **wsl --terminate <DistroName>** — terminate a specific WSL distribution  
  *Example: `wsl --terminate Ubuntu`*
- **wsl --list --verbose** — list all installed WSL distributions with status and version


---

## 📝 Notepad++

### Enable Word Wrap

1. View → Word Wrap

Enable by default:
- Settings → Preferences → Editing → Word Wrap

⚠️`NO longer use a Notepad++ i have moved to VScode`⚠️

---

## 🗃️ VScode

- **CTRL + SHIFT + P** — Search bar

Look for settings in search bar:
- Typw this ">" in the start (exmpl: >customize layout) 

Save UI by default:
- File → Save workspace as...

---

## 💡 General Tips

- Eyes open twice as fast as they close (animation timing rule)


## Related Repositories

- [CMD Repo](https://github.com/ilisho/blender-cmd-rendering-cheatsheet) — additional CMD shortcuts for batch render in Blender 


