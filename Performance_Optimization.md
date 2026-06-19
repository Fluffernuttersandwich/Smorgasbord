# 🎮 Smörgåsbord Performance Optimization Guide

This guide was written primarily for **modded 7 Days to Die**, but many of these recommendations can improve performance in other PC games as well.

Not every optimization will benefit every system. Hardware, drivers, installed mods, and personal preferences all play a role.

Depending on your configuration, these recommendations may provide anywhere from a minor improvement to a substantial increase in FPS, frame pacing, and overall smoothness.

---

# ⚠️ Before You Begin

Before making any system-level changes:

* Create a Windows Restore Point
* Back up important files
* Only change settings you understand
* If a section feels too advanced, skip it

Many of these recommendations are optional. The goal is to improve performance, not create new problems.

---

# 🚀 Performance Quick Start

Don't want to read the entire guide? Start here.

These recommendations provide the largest performance improvements for most players.

## 🟢 Highest Impact Changes

* Install 7 Days to Die, MO2, Wabbajack, and Smörgåsbord on an SSD
* Enable FrameForge upscaling (DLSS or FSR)
* Set NVIDIA Shader Cache Size to 10GB
* Cap FPS to a stable value your PC can consistently maintain
* Leave at least 100GB free on your installation drive
* Reduce or disable performance-heavy mods if needed

## 🟡 Additional Improvements

* Use Process Lasso
* Use ISLC (Intelligent Standby List Cleaner)
* Enable the "No Blurry Textures" mod if you experience texture pop-in
* Tune graphics settings for your hardware

## 🔴 Advanced Tweaking

* GPU undervolting
* GPU overclocking
* CPU tuning
* Memory tuning
* BIOS optimization

Only pursue these if you're comfortable troubleshooting stability issues.

---

# 📑 Table of Contents

* [Windows 11 Optimization](#windows-11-optimization)

  * [Important Notes](#important-notes)
  * [NVIDIA Control Panel Settings](#nvidia-control-panel-settings)
  * [Why You Should Cap Your FPS](#why-you-should-cap-your-fps)
  * [Process Lasso](#process-lasso)
  * [ISLC Memory Optimization](#islc-memory-optimization)
* [FrameForge Upscaling & Frame Generation](#frameforge-upscaling--frame-generation)

  * [GPU Recommendations](#gpu-recommendations)
  * [Recommended DLSS Presets](#recommended-dlss-presets)
  * [NVIDIA Automatic GPU Tuning](#nvidia-automatic-gpu-tuning)
* [7 Days to Die Graphics Settings](#7-days-to-die-graphics-settings)
* [Fixing Blurry Textures](#fixing-blurry-textures)
* [Mod Performance Impact](#mod-performance-impact)

  * [Performance-Heavy Mods](#performance-heavy-mods)
  * [Performance-Friendly Mods](#performance-friendly-mods)
  * [Smörgåsbord-Specific Performance Notes](#smorgasbord-specific-performance-notes)
* [Hardware & Storage Recommendations](#hardware--storage-recommendations)
* [Final Advice](#final-advice)

---

# Windows 11 Optimization

🟡 **Difficulty:** Intermediate

This video guide walks through various Windows, BIOS, and NVIDIA Control Panel optimizations designed to improve gaming performance.

**Video Guide:**
https://youtu.be/Ntkc6PeImhU

## Important Notes

* I do **not** agree with every setting shown in the video.
* The creator primarily focuses on reducing latency for competitive online gaming.
* I primarily play single-player games and generally prioritize visual quality over latency.
* Always create a Windows Restore Point before making registry changes.
* If you're uncomfortable editing the registry, skip that section.

### Windows Restore Point Guide

https://www.youtube.com/watch?v=Nm2EjpsOXms

### AMD GPU Users

If you're using an AMD GPU, ignore the NVIDIA-specific portions of the video and use this guide instead:

https://www.youtube.com/watch?v=03y1ToHieog

## NVIDIA Control Panel Settings

The two most impactful settings for most players are:

* Shader Cache Size
* Max Frame Rate

### Recommended Shader Cache Size

Set **Shader Cache Size** to:

**10GB**

This helps reduce shader recompilation and can improve smoothness in many games.

## Why You Should Cap Your FPS

Many players assume that higher FPS is always better.

For heavily modded open-world games like 7 Days to Die, that's not always true.

As you move through the world, the game constantly:

* Loads chunks
* Unloads chunks
* Streams textures
* Spawns entities
* Processes AI
* Reads data from storage

Your CPU, memory, and storage speed can all become bottlenecks.

When FPS fluctuates dramatically, those drops are often perceived as stutter.

A stable 60 FPS usually feels smoother than constantly bouncing between 45 and 100 FPS.

### Global FPS Limit

I recommend setting your global FPS limit to match your monitor's refresh rate.

For example:

* 60Hz monitor → 60 FPS
* 144Hz monitor → 144 FPS
* 165Hz monitor → 165 FPS

### Game-Specific FPS Limit

For demanding games such as heavily modded 7DtD, consider creating a per-game FPS cap.

Example:

If your FPS regularly fluctuates between:

* 40 FPS
* 90 FPS

but typically averages around:

* 60 FPS

Then cap the game to:

**60 FPS**

This often produces a smoother experience than allowing large FPS swings.

NVIDIA Control Panel is not the only way to limit FPS, but it is simple and effective.

### NVIDIA Control Panel Download

https://apps.microsoft.com/detail/9nf8h0h7wmlt

### NVIDIA App Configuration Guide

https://www.youtube.com/watch?v=j08cAZGMhTM

---

## Process Lasso

🟡 **Difficulty:** Intermediate

Process Lasso can help improve CPU scheduling and process priority behavior.

Video Guide:

https://www.youtube.com/watch?v=xXpnCqXxwz8

Download:

https://bitsum.com/

I recommend watching the tutorial at half speed while following along.

---

## ISLC Memory Optimization

🟢 **Difficulty:** Beginner

ISLC (Intelligent Standby List Cleaner) can help reduce memory-related stuttering on some systems.

Video Guide:

https://www.youtube.com/watch?v=4uTZb2nhJD8

Download:

https://www.wagnardsoft.com/forums/viewtopic.php?t=1256

---

# FrameForge Upscaling & Frame Generation

🟢 **Difficulty:** Beginner

Video Guide:

https://www.youtube.com/watch?v=qYIoBouLMzI

FrameForge is one of the most impactful performance upgrades available for 7 Days to Die players with supported hardware.

Smörgåsbord already includes the **DLSS Fix portion** of FrameForge within MO2.

If you want Frame Generation support, you must manually download and install the additional files provided by the mod author.

Download:

https://www.nexusmods.com/7daystodie/mods/6781

## What FrameForge Does

FrameForge improves performance through several technologies:

* DLSS Super Resolution (NVIDIA)
* FSR Super Resolution (AMD)
* Frame Generation
* Updated NVIDIA DLSS modules
* Improved image quality compared to vanilla DLSS implementation

Depending on your hardware, mods, and settings; gains can range anywhere from:

**+17% to +100% FPS**

while maintaining excellent image quality.

---

## GPU Recommendations

### AMD GPUs

Use:

**FSR Upscaling**

Start with:

* Quality
* Balanced

before moving to more aggressive performance presets.


Enable **FSR Frame Generation**

### NVIDIA GPUs

Use:

**DLSS Upscaling**

Recommended starting points:

* Quality

If you need additional FPS:

* Balanced
* Performance

can provide significant gains at the expense of some image quality.


Enable **FSR Frame Generation**

---

## Recommended DLSS Presets

## Within the Nvidia App, you can set the GPU's DLSS Preset

### RTX 20 & 30 Series

Recommended:

**Preset K**

### RTX 40 & 50 Series

If visual quality is your priority:

* Preset L
* Preset M

If performance is your priority:

* Preset K

### Personal Example

My system:

* RTX 5090
* DLSS Preset M in NVIDIA App
* Quality preset for DLSS Upscaling in-game

Your optimal settings may differ.

Always test for yourself.

---

## Configuring DLSS Presets

1. Update GPU Drivers
2. Install the latest NVIDIA App
3. Open the Graphics tab
4. Select either:

   * Global Settings
   * Individual Game Settings
5. Locate:

   * DLSS Override - Model Presets
6. Change:

   * Recommended → Custom
7. Select your preferred preset
8. Click Apply

### NVIDIA App Download

https://www.nvidia.com/en-us/software/nvidia-app/

---

## NVIDIA Automatic GPU Tuning

🟡 **Difficulty:** Intermediate

The NVIDIA App includes an automatic tuning feature that may provide a small performance improvement.

To use it:

1. Close unnecessary applications
2. Open NVIDIA App
3. Enable Automatic Tuning
4. Let the process complete

The process may take several hours.

I recommend starting it before bed and allowing it to run overnight.

---

# 7 Days to Die Graphics Settings

🟢 **Difficulty:** Beginner

Video Guide:

https://youtu.be/rN1r5hFoWOo

There is no universal "best" graphics configuration.

The ideal settings depend on:

* GPU
* CPU
* Available memory
* Monitor resolution
* Installed mods
* Personal preferences

Use the video above as a starting point and adjust based on your hardware.

---

## What Impacts FPS Most?

Performance in 7 Days to Die is heavily affected by:

* RWG map size
* Active mods
* NPC count
* Biome density
* Zombie count
* Shadow-producing light sources
* Entity density

Every object the game must render has a cost.

Examples include:

* Trees
* Grass
* Animals
* Zombies
* NPCs
* Decorations
* Modded blocks
* Modded POIs
* Dynamic lights

The more objects visible on screen, the harder your system must work.

Adjust settings accordingly.

---

# Fixing Blurry Textures

🟢 **Difficulty:** Beginner

If you experience:

* Blurry textures
* Texture pop-in
* Low-resolution terrain
* "PS2 Graphics" syndrome

try enabling the:

**No Blurry Textures**

mod included with Smörgåsbord.

If you're not using Smörgåsbord, you can download it here:

https://www.nexusmods.com/7daystodie/mods/7343

---

## Important Notes

This mod is highly hardware dependent.

Results vary significantly between systems.

### Potential Benefits

* Sharper textures
* Faster texture loading
* Reduced texture pop-in

### Potential Downsides

* Increased memory usage
* Occasional freeze-frame stutters
* No benefit on some systems

This mod tends to help lower-end systems and systems with limited VRAM the most.

---

# Mod Performance Impact

🟢 **Difficulty:** Beginner

Not all mods affect performance equally.

If you're struggling with FPS, consider disabling heavier mods before lowering graphics settings.

---

## Performance-Heavy Mods

| Mod                | Estimated FPS Impact   |
| ------------------ | ---------------------- |
| Better Biomes      | -30 FPS                |
| CATUI              | -20 FPS (some systems) |
| CUBP               | -15 to -30 FPS         |
| NPCCore + NPC Mods | -10 to -30 FPS         |
| The Descent        | -10 to -20 FPS         |
| CompoPack          | -5 to -20 FPS          |
| Urban Decay        | -5 to -10 FPS          |
| Rainstorm          | -1 to -5 FPS           |

These values are estimates only.

Actual impact varies based on hardware and playstyle.

---

## Performance-Friendly Mods

| Mod             | Estimated FPS Gain |
| --------------- | ------------------ |
| Less Trees      | +1 to +5 FPS       |
| Less Grass      | +1 to +5 FPS       |
| Despawn Zombies | +1 to +5 FPS       |

---

## Smörgåsbord-Specific Performance Notes

### Blood Moon Count

Vanilla 7 Days to Die typically struggles to keep more than roughly 30 active zombies consistently engaged, even when set to 64.

Smörgåsbord removes some of those limitations.

If you set:

* 64 Zombies

you will generally get 64 Zombies.

If you increase beyond 64, performance will begin dropping rapidly.

My personal system can handle 150+, but most systems cannot.

**Recommendation:** Stay at 64 or below unless you know your hardware can handle more.

---

### WalkerSim Population Density

WalkerSim's:

**ZombiePopulationDensity**

setting has a direct impact on performance.

Higher values create:

* More zombies
* More AI calculations
* Greater CPU load

For most systems:

**192** is a good starting point.

---

### The Descent

The Descent is one of the heavier content mods included in Smörgåsbord.

Recommended minimum:

**16GB System Memory**

---

### SCore Fire Spread

SCore includes an optional Fire Spread system.

While visually impressive, it can become demanding on:

* Servers
* Older CPUs
* Lower-end systems

Consider disabling it if performance becomes an issue.

---

## Additional In-Game Performance Tips

### Keep Farms Away From Your Base

Large tree farms can generate unnecessary rendering and simulation overhead.

Plant large farms away from your primary base whenever possible.

### Reduce Excessive Lighting

Every light source capable of casting shadows increases rendering cost.

Try to avoid:

* Excessive torches
* Excessive campfires
* Large overlapping light networks

### Reduce Zombie Count

If performance is still poor:

Lowering zombie count often produces a larger FPS gain than reducing graphical quality.

---

# Hardware & Storage Recommendations

🟢 **Difficulty:** Beginner

Sometimes the biggest performance improvements have nothing to do with graphics settings.

Storage speed, available disk space, memory capacity, and overall system health all play a role in game performance.

---

## Leave Free Drive Space Available

Many modern games use temporary storage while running.

If your drive is nearly full, you may experience:

* Longer loading times
* Texture streaming issues
* Increased stuttering
* Slower world generation

### Recommendation

Leave at least:

**100GB Free**

on the drive containing:

* 7 Days to Die
* Mod Organizer 2
* Wabbajack
* Smörgåsbord

More free space is generally better.

---

## Install Everything on an SSD

🟢 **Difficulty:** Beginner

If you're still using a traditional mechanical hard drive, upgrading to an SSD is one of the largest quality-of-life improvements available.

Install the following on an SSD whenever possible:

* 7 Days to Die
* MO2
* Wabbajack
* Smörgåsbord

### Benefits

* Faster game startup
* Faster loading screens
* Faster RWG generation
* Faster texture streaming
* Reduced hitching during exploration

An SSD will not magically increase FPS, but it can dramatically improve the overall smoothness of gameplay.

---

# Hardware Upgrades

🔴 **Difficulty:** Advanced

Sometimes the honest answer is:

> Your hardware has reached its limits.

Smörgåsbord is a large modlist.

If you want:

* Massive RWG maps
* Better Biomes
* NPC-heavy gameplay
* Large Blood Moons
* High graphics settings
* Dense cities

your hardware must be capable of supporting that workload.

---

## Upgrade Priority Guide

If you're considering hardware upgrades, I generally recommend the following order:

### 1. SSD

If you're still using a mechanical hard drive, upgrade this first.

### 2. Memory (RAM)

Modern modded gaming benefits greatly from:

**32GB RAM**

especially when running:

* Large modlists
* Discord
* Browsers
* Streaming software
* Monitoring tools

simultaneously.

### 3. GPU

The biggest upgrade for visual settings and FPS.

### 4. CPU

Important for:

* AI calculations
* NPC-heavy gameplay
* Large Blood Moons
* WalkerSim
* RWG generation

### 5. Everything Else

Motherboards, coolers, cases, and other components typically provide smaller gains.

---

## Undervolting & Overclocking

🔴 **Difficulty:** Advanced

Experienced users may wish to experiment with:

* GPU Undervolting
* GPU Overclocking
* CPU Tuning
* Memory Tuning

Potential benefits include:

* Lower temperatures
* Reduced power consumption
* Increased performance

However:

Every hardware model is different.

Every individual chip is different.

Always proceed conservatively.

A stable overclock is far more valuable than an unstable aggressive one.

When researching these topics, search specifically for:

* Your exact CPU model
* Your exact GPU model
* Your exact memory kit

to find guidance relevant to your hardware.

---

# Final Advice

Performance tuning is always a balancing act.

Every adjustment trades something for something else.

The goal is not necessarily to achieve the highest FPS possible.

The goal is to achieve the best overall experience for your hardware.

---

## Balance These Four Factors

### Visual Quality

How good the game looks.

### Stability

How reliably the game runs.

### Frame Pacing

How smooth the game feels.

### Hardware Limitations

What your system is realistically capable of delivering.

---

## Avoid Blindly Copying Other People's Settings

What works well for one person may perform poorly on another system.

Different players have:

* Different CPUs
* Different GPUs
* Different monitors
* Different memory configurations
* Different mod selections

Use recommendations as a starting point, not as absolute rules.

---

## Smörgåsbord's Greatest Strength

Smörgåsbord is designed around modularity.

You are not locked into a single configuration.

If performance becomes a problem:

* Adjust graphics settings
* Adjust gameplay settings
* Disable heavier mods
* Experiment with alternatives

Build the experience that works best for your hardware.

---

## Final Recommendation

Make one change at a time.

Test.

Evaluate.

Then move on to the next adjustment.

If you change ten things at once, you'll never know which one helped—or hurt—your performance.

A carefully tuned system almost always performs better than a randomly tweaked one.

Good luck, and happy surviving.
