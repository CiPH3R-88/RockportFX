# Rockport FX

> An advanced, native in-game environment and graphics control menu for **Need for Speed: Most Wanted (2005)**.

Rockport FX gives you complete real-time control over the game's Time of Day, weather conditions, lighting engine, and post-processing. Built natively with ImGui and DirectX 9, it bypasses traditional limits to let you customize the look of Rockport City exactly how you want it, on the fly.

---

## Features

- **Time & Weather Control** — Precise slider to change the Time of Day. Speed up the time cycle, slow it down, or freeze it completely. Toggle between Sunny/Overcast and force rain instantly.
- **Live Lighting Editor** — Edit the game's internal RGBA lighting values in real-time. Customize Ambient, Diffuse, Fog, and Sky colors, along with Environment Brightness and Car Specular intensity across all weather states.
- **Visual Treatment Tweaker** — Toggle High/Low visual treatment and Overbright on demand. Live-edit Color Tint, Bloom intensity, and Saturation.
- **Advanced Curve Canvas** — Built-in interactive spline editor to fine-tune Black Bloom and Color Bloom curves across four nodes (Shadows, Mid-Low, Mid-High, Highlights).
- **Smart Preset System** — Save your custom environments as `.nfsms` presets. The mod automatically remembers your active preset and loads it flawlessly on your next game launch.

---

## Installation

Simply drag and drop the `scripts` folder from `RockportFX.zip` into your game folder.

---

## Usage

| Action | Description |
|--------|-------------|
| `F11` | Toggle the Rockport FX menu open and closed |
| Presets tab | Create, save, or switch between lighting setups |
| Reset buttons | Resync the engine to vanilla defaults after editing Low/High VT toggles or Weather modes |

---

## Configuration

Open `scripts\RockportFX\config.yml` in any text editor to customize menu behavior:

- **`togglekey`** — Change the menu hotkey (default: `122` = F11). *Note: Requires a game restart to take effect.*
- **`menuscale`** — Adjust the UI scale for your screen resolution.
- **`debug console`** — Enable or disable the developer debug console.

---

## Troubleshooting

If the mod does not appear in-game, try one of the following:

- Set `Windowed mode = 1` in `widescreenfixsettings.ini`
- Place the [DXVK x32 d3d9.dll](https://github.com/doitsujin/dxvk/releases/tag/v2.7.1) into your game folder

---

## Credits

- ARCHIE
- blueskywestside
- Elaymm
- HellRaven
- nlgxzef
- Osdever
- Torutheredfox
- VeeTec
