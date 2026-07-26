# EVA Clock :Rebirth

**English** | [日本語](README.ja.md)

---

EVA Clock: Rebirth

April 12, 2026 — Breaking 23 years of silence, it finally reawakens.

Built upon the classical code etched in the Carbon architecture,
its core has been reconstructed with the aid of Claude Code,
the very embodiment of modern technological ingenuity.

Image data, once dormant within a G4-era Mac, has been salvaged and reborn in high resolution—
reviving, in vivid clarity, the awe and emotion of its original era.

The memory, preserved exactly as it was.
And now, a new resurrection begins.

2026 — Rebirth.

<img width="493" height="211" alt="EVA Clock Rebirth" src="https://github.com/user-attachments/assets/db7504a6-fb8d-4783-9b0b-d5bdb88a0d4c" />

---

## 📥 Download

[**Download the latest release (GitHub Releases)**](https://github.com/EVAtiter/EVA-Clock-Rebirth/releases/latest)

Unzip the archive and drag `EVA Clock Rebirth.app` into your `Applications` folder. The app is notarized by Apple, so it launches without any Gatekeeper warning.

If you use Homebrew, you can install it this way instead.

```
brew install --cask EVAtiter/tap/eva-clock-rebirth
```

To update an existing Homebrew installation:

```
brew update && brew upgrade --cask EVAtiter/tap/eva-clock-rebirth
```

---

## What EVA Clock:Rebirth Can Do

A clock that lives on your macOS desktop, styled after the interface of a certain organization. It is not just a look — it shows genuinely useful information and can be customized down to the details.

<img width="480" height="210" alt="EVA Clock:Rebirth screenshot" src="https://github.com/user-attachments/assets/771468c8-2ff7-49eb-ad80-f73ad9ea8489" />

### 🕐 Time and "unit status" readout
- Hours, minutes and seconds on an LED-style panel, updated in real time
- **Battery level and remaining time** (MacBook models). Switching between internal and external power triggers an animation
- **Power draw** shown in four stages: SNAIL / SLOW / NORMAL / RACING
- **CPU load and power draw** as a time-series graph (Split / Overlay display modes)
- **GPU / ANE load** as gauges (Apple Silicon)

### 📊 Standalone meter window
- A **small meter-only window**, separate from the clock
- Size, opacity and position are configured independently from the clock

### 🎨 Dress it up with skins
- Five skins are bundled. Switch from **Settings → Clock → Appearance → Skin**, or by **right-clicking the clock → Skins**
- **Since v2.14.0, the skin is a per-window setting.** When you show clocks on several monitors, each one can wear a different skin
  - `Rebirth` … the new design (default)
  - `Legacy` … the original design
  - `Steampunk` … a brass-framed mechanical chronometer. Ten unlit cathode digits sit stacked inside each tube; raise the opacity and only the tubes and their brass sockets remain
  - `Star Trek` … an LCARS-style bridge console. Raise the opacity and only the frame and the digits remain
  - `NixieTube` … the orange glow of cold-cathode tubes. Raise the opacity and only the tubes are left on your desktop
- **You can build your own skin too** — just images plus a settings file. See
  **[SkinGuide.md](SkinGuide.md)** (Japanese) for the full format reference and a
  copy-paste prompt that lets an AI generate the layout file for you

### 🖥 Multi-display support
- Show the clock on **several monitors at once** ("display targets / mirror" feature)
- **Size, position, opacity and skin are all adjusted per window**

### 🪶 Light and considerate
- **Light on CPU and power** even while resident (the multi-window case is optimized too)
- **Steps aside automatically during fullscreen video** and comes back when you are done
- Keep on top, lock the position, resize from 25% to 200% — place it however you like

### ✅ Safe to use
- **Free** and **notarized by Apple** (launches without warnings)
- **Apple Silicon (arm64) only**
- Requires **macOS 13.0 Ventura or later**
