<div align="center">
  <img alt="GlazeWM" src="https://i.ibb.co/Q3w46sx2/glazewm-logo.png" width="60">
</div>

<div align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/GlazeWM-3.7-blue?style=flat-square&labelColor=1e1e2e">
  <img alt="Static Badge" src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square&labelColor=1e1e2e">
</div>

# GlazeWM Config

A clean, minimal **GlazeWM** config with themed workspaces, vim-style navigation, and sensible defaults.

---

## ✨ Features

| Feature                  | Description                                                  |
| ------------------------ | ------------------------------------------------------------ |
| **Focus follows cursor** | Windows focus as you move your mouse — no clicking needed    |
| **Cursor jump**          | Automatically warps cursor to the focused window             |
| **Cloak hide method**    | Modern, stable workspace switching without animations        |
| **Themed workspaces**    | Five named workspaces: Swing, Weave, Node, Beats, Void       |
| **Dual-monitor**         | Workspaces pinned to specific monitors out of the box        |
| **Vim-style keys**       | `Alt+h/j/k/l` for direction focus & resize                   |
| **Sanitary gaps**        | 7px inner / 7–9px outer gaps, DPI-aware                      |
| **Floating defaults**    | New floating windows are centered and always-on-top          |
| **Smart window rules**   | PiP, Office apps, PowerToys, Lively — all handled gracefully |
| **Toggle-able**          | Pause/resume window management with `Alt+Shift+P`            |

---

## ⌨️ Keybindings

| Keys                  | Action                              |
| --------------------- | ----------------------------------- |
| `Alt + H / L`         | Focus left / right                  |
| `Alt + Shift + H / L` | Move window left / right            |
| `Alt + J / K`         | Resize width -2% / +2%              |
| `Alt + 1–5`           | Focus workspace 1–5                 |
| `Alt + Shift + 1–5`   | Move window → workspace 1–5         |
| `Alt + Shift + A / F` | Move workspace left / right monitor |
| `Alt + C`             | Close window                        |
| `Alt + M`             | Minimize window                     |
| `Alt + F`             | Toggle floating (centered)          |
| `Alt + T`             | Toggle tiling                       |
| `Alt + Shift + P`     | Pause / resume tiling               |
| `Alt + Shift + R`     | Reload config                       |

---

## 🗂️ Workspaces

| Key     | Name  | Purpose                | Monitor   |
| ------- | ----- | ---------------------- | --------- |
| `Alt+1` | Swing | Browsing & Apps        | Monitor 0 |
| `Alt+2` | Weave | Development            | Monitor 1 |
| `Alt+3` | Node  | Social / Chatting      | Monitor 1 |
| `Alt+4` | Beats | Music                  | Monitor 0 |
| `Alt+5` | Void  | Buffer & misc          | Monitor 0 |

---

## 🚀 Getting started

1. Install [GlazeWM](https://github.com/glzr-io/glazewm)
2. Replace `%USERPROFILE%\.glazewm\config.yaml` with this file
3. Reload with `Alt+Shift+R` (or restart GlazeWM)

---

## 📁 File structure

```text
glazewm-config/
└── config.yaml        # Main GlazeWM configuration
```
