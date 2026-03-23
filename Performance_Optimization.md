# 🎮 Performance Optimization Guide for PC Gaming

Not all suggestions apply equally to every system.  

Many of the options are hardware specific, or based on personal preference.

If you do everything in this guide, you could see a 2-30% boost to FPS in your gaming.

Your mileage may vary.

This guide was written primarily for modded 7DtD, but much of it can be beneficial for any PC Game.

---

# 1️⃣ Optimizing Windows 11 for Gaming

This video guide walks through various Windows, BIOS, and NVIDIA Control Panel optimizations to improve gaming performance:

▶ https://youtu.be/Ntkc6PeImhU

### Important Notes

- I do **not** agree with every setting shown in the video.
- The creator primarily focuses on **latency reduction for competitive online gaming**.
- I personally play single-player and prioritize **visual quality over latency**.
- **Before you make any changes to regedit, make a Windows Restore Point as a back-up!**
- _If you don't feel comfortable doing the regedit portion, just skip it._

How to make a Windows 11 Restore Point: https://www.youtube.com/watch?v=Nm2EjpsOXms


### Example Difference

- I leave **VSync enabled in NVIDIA Control Panel**
- I disable **VSync in-game**

Feel free to experiment based on your priorities:
- Competitive latency
- Visual fidelity
- Frame pacing stability


The two most important settings in the Nvidia Control Panel are Max Frame Rate and Shader Cache Size.


Set Shader Cache Size to 10GB.


## Max Frame Rate and why you should cap your FPS:

You are playing an open world voxel game with mods. 
When you move around the world, the game loads and unloads stuff. 
Your CPU, Memory, and even storage-read speeds become bottlenecks. 
Any sudden drop of FPS will be perceived by you as stuttering, so a workaround is to cap FPS closer to the lower bound _your PC can deliver at a constant rate no matter what._


Globally (for all applications), I set Max Frame Rate to my monitors Max Refresh Rate. 

My Display's Max Refresh Rate is 165Hz, so I set my Max FPS Rate to 165 as well.

However, you can and should cap FPS by Application for games like 7DtD.
On each intensive (or heavily modded overhaul) game, you should test it yourself.
On some older titles like Skyrim and Fallout New Vegas, you want to cap FPS to 60, but then use other tools for Frame Generation.

Generally you want to lock an individual game's Max FPS Rate to the average FPS you get in your (modded) game.

Let's say your FPS for Smorgasbord bounces between 40 and 90 FPS, but mostly hangs out at 60. You should lock your FPS to 60.

Nvidia Control Panel is _not_ the only way to lock FPS, there are other applications and methods, but this one works fine.


**Global Setting**
<img width="2012" height="1464" alt="image" src="https://github.com/user-attachments/assets/708a66a3-3245-4760-9942-2aee6aa50b60" />


**Application Setting**
<img width="1458" height="1138" alt="image" src="https://github.com/user-attachments/assets/dc2c97ae-ce40-48c1-a839-c5edeba96f3c" />



You can download the Nvidia Control Panel from here:

https://apps.microsoft.com/detail/9nf8h0h7wmlt?hl=en-US&gl=US


---


## Use Process Lasso to maximize your CPU for gaming

https://www.youtube.com/watch?v=xXpnCqXxwz8

https://bitsum.com/

I recommend you watch this video at half-speed to follow along.


---

## ISLC (Intelligent Standby List Cleaner) for Memory (RAM) - Boost FPS and Reduce Latency!


https://www.youtube.com/watch?v=4uTZb2nhJD8


https://www.wagnardsoft.com/forums/viewtopic.php?t=1256


---



# 2️⃣ Super Resolution Mod (Included in MO2)

The Smorgasbord Mod List already includes this mod in Mod Organizer 2 (MO2).

If you are not using Smorgasbord, you can download **Super Resolution** from here:

https://www.nexusmods.com/7daystodie/mods/6781


This mod enables GPU-specific Upscaling options inside 7DtD’s video settings to improve FPS without heavily sacrificing visuals.


<img width="2308" height="764" alt="image" src="https://github.com/user-attachments/assets/7c9d8aaf-dd20-4c0b-ad8c-386f634569a9" />


---

## GPU Options

### AMD GPUs
- Use **FSR**

### NVIDIA GPUs
- Use **DLSS**
- To maximize performance, you may choose to experiment with lower presets like:
  - Balanced
  - Performance

I personally use a 5090, with the Nvidia App DLSS Preset M, and in-game DLSS Preset on Ultra Quality or DLAA for 7DtD.

The 7DtD Super Resolution mod is only for Windows OS! Not Linux, not Mac.

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


You can download the Nvidia App from:

https://www.nvidia.com/en-eu/software/nvidia-app/


Inside the Nvidia App, you can also Automatically Tune your GPU for a slight performance bump. 

Close all other applications, toggle the button in this screenshot, and let it run. 

It may take a few hours, it's best to launch this process prior to going to bed and letting it run overnight.


<img width="2880" height="1674" alt="image" src="https://github.com/user-attachments/assets/848e0349-5d72-4643-8fae-50981cb73d7a" />


To enable the Nvidia Overlay within the Nvidia App:


<img width="2856" height="1470" alt="image" src="https://github.com/user-attachments/assets/b1cb09a3-79ba-400d-ba2e-1566a121c7c0" />


You can edit your overlay's display setting like this:

Press Alt+z to get into the Nvidia Overlay once you toggled it to be availabe within the app. 

Then click the "Statistics" button at the bottom.


<img width="1022" height="2158" alt="image" src="https://github.com/user-attachments/assets/2b488fe5-49f0-4ec2-bfc0-eb6077a01b00" />


<img width="1013" height="1390" alt="image" src="https://github.com/user-attachments/assets/7384fb3a-5c73-4389-a6a6-5d006a6147a1" />


<img width="3838" height="1470" alt="image" src="https://github.com/user-attachments/assets/1c86ba34-ec3c-4f8a-8925-954be82b40ac" />



---

# 3️⃣ 7DtD In-Game Graphics Settings

Follow this guide and adjust according to your hardware and personal preferences:

▶ https://youtu.be/rN1r5hFoWOo

### Key Reminder

Your performance depends heavily on:
- RWG map size
- Active mod selection
- NPC usage
- Biome density mods
- Number of entities and shadow-producing light sources on screen

The more objects and shadows the game has to render, the harder it is on performance.  
Trees, grass, animals, zombies, NPCs, light sources, debris, decorations, modded blocks, modded POIs, etc. 
Adjust accordingly.

---

# 4️⃣ Fixing Low Resolution & Blurry Textures in 7DtD


<img width="882" height="802" alt="image" src="https://github.com/user-attachments/assets/575db94c-991c-4a9e-88da-8342450cb12a" />


If you experience:
- Blurry texture pop-in
- Low-resolution textures loading slowly (PS2 graphics)

Enable the **“No Blurry Textures”** mod in MO2.


If not using Smorgasbord, you can download the mod from here:

https://www.nexusmods.com/7daystodie/mods/7343


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
| The Descent Mods | -10 to -20 FPS |
| Rainstorm | -1 to -5 FPS |


Note: For the WalkerSim mod specifically, ZombiePopulationDensity will effect your FPS. 
The higher the number, the more FPS you will lose.


SCore adds Fire-Spreads features. This can be demanding on servers and low-end hardware. 


---

## 🟢 Performance-Improving Mods

| Mod | Estimated FPS Gain |
|------|--------------------|
| Less Trees | +1 to +5 FPS |
| Less Grass | +1 to +5 FPS |
| TMO’s Performance Plus | +5 to +10 FPS |
| Despawn Zombies | +1 to +5 FPS |


### In game tips to prevent uneccessary FPS loss: 
- Don't plant too many trees or plants near to your base. Keep your tree farm far away from your base.
- Don't use too many lights/torches/fires. Overlapping lights makes your game work harder than it needs to. 
- Maybe lower the number of zombies in the in-game settings if you are really struggling.  


---

# 6️⃣ Additional Performance Tips

### A. Leave Free Drive Space

Leave **at least 100GB free** on the drive where:
- The game is installed
- The modlist is installed

Games use overhead storage during runtime, if you don't have any, it can cause a slowdown.

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

### :duck:  C. Consider Lossless Scaling (LS)

Try **Lossless Scaling’s Frame Generation**. 

It costs $7USD on Steam, but occasionally goes on sale for less.

It can add Upscaling and Frame Generation to games that don't natively support it.

This can often double your FPS with "fake frames" in many games.

Here's a guide on LS:
https://youtu.be/fCOEDTfLsSs


<img width="2246" height="1626" alt="image" src="https://github.com/user-attachments/assets/6d85385b-3095-48de-9794-3139060f1034" />


Avoid going down the:
> “Dual-GPU optimization rabbit hole”
Dual-GPU Lossless Scaling is rarely worth the effort. 

It's more hassle than it's worth.

Minimal performance boost, doesn't work on many games, or is a hassle to get it to work.

I speak as someone with expereince, don't bother with Dual-GPU LSFG. 

Just save up $, and upgrade your main GPU and other components.


For some games (not 7DtD), you can also investigate "**PureDark**". 

It's a pay-for application, but it's incredible for games like modded Skyrim.

---

### :computer:  D. Upgrade Your Hardware

Sometimes the honest answer is:

> You have reached the limits of your current system.

Smörgåsbord is not a lightweight modlist.

If you want:
- Ultra visuals
- Heavy biome mods
- Dense NPCs
- Massive RWG maps

You need hardware capable of supporting that.


**For Advanced Users**: you could also look into undervolting, and overclocking your hardware. 

This is very hardware-model and unique hardware-piece specific.

You can go to YouTube, and look up your specific GPU/CPU/Memory and try to squeeze a bit more out.
I was able to safely undervolt and overclock my GPU, and give my CPU a slight bump. 
However, my Memory didn't win the "Silicon Lottery", and I can only use the normal BIOS EXPO/DOCP boost.
Any time you experiment with overclocking and undervolting your components, always err to a conservative setting.


---

# Final Advice

Performance tuning is always a balance between:

- Visual quality
- Stability
- Frame pacing
- Hardware limitations

For 7DtD, Smörgåsbord gives you modular control of your mods — use it wisely.

Adjust settings intentionally.

Don’t blindly copy someone else’s configuration.
