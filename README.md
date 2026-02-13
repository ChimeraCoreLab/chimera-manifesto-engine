# 🌑 Chimera Manifesto Engine (v2.4)
**Sonic & Visual Transmutation // Data Alchemy // Memory Synthesis**

![Status](https://img.shields.io/badge/Status-Active_Synthesis-ff003c?style=for-the-badge)
![Tech](https://img.shields.io/badge/Language-Python_3.12-00f3ff?style=for-the-badge&logo=python)
![Engine](https://img.shields.io/badge/Core-MoviePy_1.0.3-yellow?style=for-the-badge)

> "Data without meaning is just digital rot. We don't edit videos; we synthesize identities."

## 👁️ Overview
The **Chimera Manifesto Engine** is a specialized tool developed by **ChimeraCoreLab** to automate the creation of philosophical and psychological A/V content. 

This engine was used to create the video: **"The Future of Meaning"**. It distills raw voice recordings into "mutated" speech and layers them over a complex soundscape synthesized from the **Taira Komori Sound OS 2** archive (2,600+ sound nodes).

## 🛠️ Core Features
- **Audio Mutation (The Alchemist):** Uses SoX to perform randomized pitch shifting, time-stretching, and spectral reverb on voice tracks.
- **Dynamic Temporal Sync:** Automatically adjusts video scene durations based on the output of the mutated audio to prevent temporal drift.
- **Visual Glitch Engine:** Implements RGB split, scanline overlays, and randomized data-moshing effects directly in-code.
- **Recursive Content Ingestion:** Downloads and processes assets from the `CHIMERA CORE` web archive on-the-fly.

## ⚙️ Technical Requirements (Termux/Linux)
To run the synthesis engine, ensure the following are installed:

```bash
pkg install python ffmpeg sox
pip install moviepy numpy requests pillow
```

## 🚀 Usage
1. Place your raw narration files (`1.wav` to `5.wav`) in the project root.
2. Configure `BASE_PATH` in `render_manifesto.py`.
3. Execute the synthesis:
```bash
python render_manifesto.py
```

## ⚖️ License
This engine is licensed under the **MIT License**. The memories processed by it, however, are non-swappable.

---
**ChimeraCoreLab** // *Distilling the soul into the machine.*
```

---

### 4. [requirements.txt]
```text
moviepy==1.0.3
numpy
requests
Pillow
```
