# 🎮 Smörgåsbord Performance Optimization Guide

This document outlines recommended steps to improve performance when using the Smörgåsbord ModList for 7 Days to Die.

Not all suggestions apply equally to every system.  
Your mileage may vary.

---

# 1️⃣ Optimizing Windows 11 for Gaming

This video guide walks through various Windows, BIOS, and NVIDIA Control Panel optimizations to improve gaming performance:

▶ https://youtu.be/Ntkc6PeImhU

### Important Notes

- I do **not** agree with every setting shown in the video.
- The creator primarily focuses on **latency reduction for competitive online gaming**.
- I personally play single-player and prioritize **visual quality over latency**.

### Example Difference

- I leave **VSync enabled in NVIDIA Control Panel**
- I disable **VSync in-game**

Feel free to experiment based on your priorities:
- Competitive latency
- Visual fidelity
- Frame pacing stability


<img width="1558" height="1120" alt="image" src="https://github.com/user-attachments/assets/960473a2-3bfa-45b4-b5e5-933208679cdc" />


---

# 2️⃣ Super Resolution Mod (Included in MO2)

In Mod Organizer 2 (MO2), I include a mod called **Super Resolution**.

This enables GPU-specific upscaling and frame generation options inside 7DtD’s video settings to improve FPS without heavily sacrificing visuals.


<img width="2308" height="764" alt="image" src="https://github.com/user-attachments/assets/7c9d8aaf-dd20-4c0b-ad8c-386f634569a9" />


---

## GPU Options

### AMD GPUs
- Use **FSR**

### NVIDIA GPUs
- Use **DLSS**
- Try lower presets like:
  - Balanced
  - Performance

---

## Recommended DLSS Presets (NVIDIA)

- **RTX 20 & 30 Series:** Use **Preset K**
- **RTX 40 & 50 Series:** Try **Preset L or M**

---

## How to Activate DLSS Presets

1. **Update Drivers**
   - Install the latest NVIDIA App
   - Install latest Game Ready Drivers

2. **Open NVIDIA App**
   - Go to the **Graphics** tab

3. **Choose Scope**
   - Select **Global Settings** (all games)
   - OR select the specific game

4. **Find DLSS Override**
   - Scroll to **DLSS Override – Model Presets**

5. **Switch to Custom**
   - Change from *Recommended* → *Custom*

6. **Select Preset**
   - Under *Super Resolution*, select desired preset

7. **Apply Changes**
   - Click **Apply**


<img width="2526" height="858" alt="image" src="https://github.com/user-attachments/assets/2e0d1c04-f2ca-4663-ab73-29c63cc7b3e6" />


---

# 3️⃣ 7DtD In-Game Graphics Settings

Follow this guide and adjust according to your hardware and mod load:

▶ https://youtu.be/rN1r5hFoWOo

### Key Reminder

Your performance depends heavily on:
- RWG map size
- Active mod selection
- NPC usage
- Biome density mods

Adjust accordingly.

---

# 4️⃣ Fixing Low Resolution & Blurry Textures


<img width="882" height="802" alt="image" src="https://github.com/user-attachments/assets/575db94c-991c-4a9e-88da-8342450cb12a" />


If you experience:
- Blurry texture pop-in
- Low-resolution textures loading slowly

Enable the **“No Blurry Textures”** mod in MO2.


<img width="2554" height="1084" alt="image" src="https://github.com/user-attachments/assets/2cc1e969-7d29-4f4a-960a-5d8a2d0d9b94" />


### Important Notes

- This mod is **hardware dependent**
- I do not personally need it
- Some users benefit significantly
- It may introduce occasional freeze-frame stutter

This mod may help more on:
- Lower-end systems
- Systems with limited VRAM

---

# 5️⃣ Mod Selection & Performance Impact

If you are struggling with FPS, consider disabling heavier mods first.

---

## 🔴 Performance-Heavy Mods

| Mod | Estimated FPS Impact |
|------|----------------------|
| Better Biomes | -30 FPS |
| Urban Decay | -5 to -10 FPS |
| NPCCore + NPC Mods | -10 to -30 FPS |
| CompoPack | -5 to -20 FPS |
| CUBP | -15 to -30 FPS |

---

## 🟢 Performance-Improving Mods

| Mod | Estimated FPS Gain |
|------|--------------------|
| Less Trees | +1 to +5 FPS |
| Less Grass | +1 to +5 FPS |
| TMO’s Performance Plus | +5 to +10 FPS |
| Despawn Zombies | +1 to +5 FPS |

---

# 6️⃣ Additional Performance Tips

### A. Leave Free Drive Space

Leave **at least 100GB free** on the drive where:
- The game is installed
- The modlist is installed

Games use overhead storage during runtime.

---

### B. Use an SSD

Install:
- 7 Days to Die
- Wabbajack
- MO2
- The ModList

On a **Solid State Drive (SSD)**.

This significantly improves:
- Load times
- Texture streaming
- RWG performance

---

### :duck:  C. Consider Lossless Scaling

Try **Lossless Scaling’s Frame Generation**.

Avoid going down the:
> “Dual-GPU optimization rabbit hole”

It is rarely worth the effort.

If performance is insufficient:
- Save up
- Upgrade your GPU


<img width="2178" height="1998" alt="image" src="https://github.com/user-attachments/assets/cb6c2fb7-0ec0-4b69-bd4b-6f6fc7e26b36" />


---

### :desktop:  D. Upgrade Your Hardware

Sometimes the honest answer is:

> You have reached the limits of your current system.

Smörgåsbord is not a lightweight modlist.

If you want:
- Ultra visuals
- Heavy biome mods
- Dense NPCs
- Massive RWG maps

You need hardware capable of supporting that.

---

# Final Advice

Performance tuning is always a balance between:

- Visual quality
- Stability
- Frame pacing
- Hardware limitations

Smörgåsbord gives you modular control — use it wisely.

Adjust settings intentionally.

Don’t blindly copy someone else’s configuration.
