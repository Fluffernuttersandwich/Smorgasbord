# 🎥 Streamer & Content Creator Considerations

This page contains tips and recommendations for streamers, YouTubers, screenshot artists, and other content creators using Smörgåsbord.

If you are streaming/recording using Smorgasbord, feel free to reach out to me in a DM on Discord for assistance as needed.  


# Table of Contents

## 📸 1. Screenshots

* [1.1 Built-In Screenshots (F9)](#11-built-in-screenshots-f9)
* [1.2 NVIDIA Screenshots (Alt+F1)](#13-nvidia-screenshots-altf1)

## 🎬 2. Recording & Streaming

* [2.1 OBS Recommendations](#21-obs-recommendations)

## ⚙️ 3. Performance Considerations

* [Performance Considerations](#3-performance-considerations)

## 🎨 4. Thumbnail Creation Tips

* [4.1 Useful Console Commands](#41-useful-console-commands)

## 🧟 5. Mod Considerations for Creators

* [Mod Considerations for Creators](#5-mod-considerations-for-creators)

## 6. Exporting Your Custom Profile to share with Community Members

* [Exporting Your Custom Profile to share with Community Members](#6-exporting-your-custom-profile-to-share-with-community-members)

## 🛠️ 7. Twitch Chat Commands

* [7 Twitch Chat Commands](#7-twitch-chat-commands)

## 🎵 8. Music & Copyright

* [Music & Copyright](#8-music--copyright)

## ⭐ 9. Featured Content Creators

* [Featured Content Creators](#9-featured-content-creators)

## ❤️ 10. Thank You

* [Thank You](#10-thank-you)

---

1. Screenshots

Capturing high-quality screenshots is essential for thumbnails, social media posts, bug reports, and promotional content.

1.1 Built-In Screenshots (F9)

Normally most of you Launch your game from Steam and use the F12 key to take screenshots... 

Since we are launching the game from MO2 (and _not_ Steam), the F12 key will not work, so here is an easy workaround:

7 Days to Die includes a built-in screenshot function.

Default Key:

F9

Screenshots are saved to:

%AppData%\Roaming\7DaysToDie\Screenshots

This is often the easiest method when launching the game through Mod Organizer 2, since Steam's F12 screenshot functionality may not always attach correctly when launching through MO2.

---

1.2 NVIDIA Screenshots (Alt+F1)

For NVIDIA users:

Alt + F1

Advantages:

Full-resolution screenshots
Independent of Steam Overlay
Reliable with Mod Organizer 2

---

2. Recording & Streaming

2.1 OBS Recommendations

For most users:

Game Capture

provides the best performance.

Alternative methods:

Window Capture
Display Capture

---

3. Performance Considerations

Please see the Performance Optimization Guide for mod selection and setting recommendations ➡ **[Performance_Optimization.md](Performance_Optimization.md)**

When using a heavy Mod List like Smorgasbord + OBS, it's normal for the game to stutter for the first 2-3 minutes when you first load in. 

On most systems, this should stop after 2-3 minutes.

If recording or streaming causes performance issues, consider reducing:

- Shadow Distance
- Reflection Quality
- Water Quality
- Dynamic Mesh Distance
- Dynamic Resolution (if desired)

These settings generally provide the largest performance gains with minimal visual impact during gameplay recordings.

---

4. Thumbnail Creation Tips

Creating thumbnails often requires screenshots that are difficult to capture during normal gameplay.

4.1 Useful Console Commands

Enable Debug Menu:

dm

Enable God Mode:

god

Enable Fly Mode:

fly

Toggle HUD:

F7

Pause Time:

st

These commands can help stage screenshots and cinematic scenes.

5. Mod Considerations for Creators

Smörgåsbord intentionally adds:

- More zombie variety
- Expanded clothing, armor, vehicle, decor, and weapon variety
- Additional points of interest
- Additional ambient encounters


As a result:

- Gameplay footage may differ from vanilla.

- Screenshots may contain content unfamiliar to viewers.

- Unique encounters can occur that are not present in a standard game.

- This is normal and expected behavior.


> [!CAUTION]
> I would strongly recommend a brief test game with the mods you selected prior to commiting to a stream or long-format playthrough!
>
> This is so you have time to figure out if you dislike a mod prior to commiting.
> 
> Some mods can be toggled mid-save, some cannot be toggled mid-save.
>  
> I made the default Smorgasbord Profile in MO2 Streamer friendly, but you should still run a test game prior to running it live to tailor your experience to you and your audience. 

---

### Byteblazar's Screamers 

This makes Screamers move at hyper-speed and try to flee from the player. 

Since they don't stop screaming, this can become audibly annoying for your audience.

This mod is disabled by default, and I encourage you to keep it disabled for streaming.

---

### WalkerSim is intentionally challenging! 

If it's too much, you can lower the Zombie PopulationDensity in the WalkerSim.xml file. 140 is good for most, but I like 192 for the challenge.

<img width="2284" height="2036" alt="image" src="https://github.com/user-attachments/assets/d1a132f7-6be4-4617-841e-2a07c7f310f3" />


You can safely edit or disable/enable this mod mid-save, it is save-safe to do so. 

---

### EFTX: The default list includes hundreds of new ammo types. 
If this is too much of a hassle for you to want to manage, you can disable the current Z2 ammo mod, and enable one of the "Vanilla" Z2 ammo options. 

You can refer to ➡ **[EFTX_for_Dummies.md](EFTX_for_Dummies.md)**

---

### Peek Lean: Either disable or map out the buttons.
You can either disable this mod in MO2 if you don't plan to use it, or you can remap the buttons in the in-game Mods (Gears) menu:
<img width="2726" height="1500" alt="image" src="https://github.com/user-attachments/assets/da045251-4e80-43b5-bd61-db5a5dc97341" />

---

### Ultra-Dark-Night and Medical Conditions mods: I'd strongly discourage using these mods for a stream

These mods are disabled by default, 

They make for a bad visual experience for users watching your game.

From a user perspective, I enjoy these mods when not recording, but as a content consumer, any mod/overhaul that includes visual reducers makes for a bad experience.

Medical Conditions: Adds some eye-sight related ailments that include on-screen effects like blurry vision. 


Ultra-Dark-Night mods: Makes it so dark the players can hardly see what is going on at night, and/or makes it difficult to drive.


<img width="2622" height="198" alt="image" src="https://github.com/user-attachments/assets/4eefc4cd-86b5-4feb-8ebe-3a5b7ee86333" />

---

### Better Biomes, NPC-CORE, CATUI, and other "Heavy Mods"
Even if you are rocking a 5090, "Heavy Mods" + the rest of Smorgasbord + OBS is very resource intensive. 
I would not recommend using any heavy mods for a stream/recording.

Please see the Performance Optimization guide for Performance-Heavy Mods. 

➡ **[Performance_Optimization.md](Performance_Optimization.md)**


## Adding Your Own Mods

I have helped streamers add their own Decor Mods, and Community Member zombie names over health bar mods in MO2. 

Most small mods like these can easily be added to MO2 without issue.

These are reasonable accomodations, I am willing to help you with this. For content creators specifically, since you are willing to showcase my mod list, I am willing to help you customize your experience. 

But, keep it reasonable, I am not a miracle worker, I can't get Darkness Falls + Rebirth + Smorgasbord to work for you in one game. :P 

For step by step guidance to add your own mods, you can refer to ➡ **[ADDING_YOUR_OWN_MODS.md](ADDING_YOUR_OWN_MODS.md)**

> [!WARNING]
> **Suggestion:** Make a copy of the Smorgasbord Profile in MO2, give it your name with [NoDelete] in front of it.
> 
> Also put [NoDelete] in front of any added mods
> 
> Now any mods you toggled, or added will be remembered should you update the Smorgasbord Mod List through Wabbajack.
>
> Remember, it's best to not update the Mod List or toggle mods mid-save. Some updates are minor, and some mods can be safely toggled, but some cannot.
> 
> I don't want your established playthrough to become broken. It would be a good idea to make backups and write down what mods you toggled, just in case.

For step by step guidance in creating your own Profile, you can refer to ➡ **[Saving_Toggled_Mods_as_a_Profile_for_Smorgasbord_Updates.md](Saving%20Toggled%20Mods%20as%20a%20Profile%20for%20Smorgasbord%20Updates.md)**

---

6. Exporting Your Custom Profile to share with Community Members

In MO2, right-click a mod, 

---

7. Twitch Chat Commands

If you're streaming Smörgåsbord, viewers will often ask:

* What mods are you using?
* Is this an overhaul mod?
* How do I install it?
* Where can I download it?

Creating a simple Twitch chat command can save a tremendous amount of time during a stream.

---

## !mods Command

Recommended Nightbot, StreamElements, or Streamer.bot command:

```text
Here is the list of mods included for you to select in the Smörgåsbord Mod List: https://www.nexusmods.com/games/7daystodie/collections/3olqbw/mods
```

---

## Short Version

If your bot has character limits:

```text
Smörgåsbord Mod List: https://www.nexusmods.com/games/7daystodie/collections/3olqbw
```

---

## Suggested Additional Commands

### !smorgasbord

```text
Smörgåsbord answers the question: "What if vanilla 7 Days to Die had ten years of community improvements layered onto it?" Download: https://www.nexusmods.com/games/7daystodie/collections/3olqbw
```

### !modlist

```text
Want the same mods I'm using? Grab the Smörgåsbord collection here: 
```

_Add a link to your custom Profile exported .csv list of selected mods in Smorgasbord._

### !discord

```text
Need help installing or troubleshooting Smörgåsbord? Visit the Smörgåsbord Discord support channels and installation guides available from the GitHub page: https://github.com/Fluffernuttersandwich/Smorgasbord/blob/main/README.md
```

---

## 💡 Creator Tip

Viewers frequently discover Smörgåsbord through Twitch streams and YouTube videos. Adding a simple !mods command allows interested viewers to quickly find the collection without interrupting gameplay or requiring repeated explanations during a stream.

This is especially useful during horde nights, challenge runs, and high-viewer-count moments when chat activity is at its highest.

---

8. Music & Copyright

The default Smörgåsbord Mod List itself does not use any copyrighted music for gameplay.

### Shameless Plug: all music from my own video recordings now comes from Stormwrought Audio.
Stormwrought Audio is my other YouTube channel. 

You can use any of that music for license free, royalty free, stream-safe videos. 

https://www.youtube.com/@StormwroughtAudio 

---

9. Featured Content Creators

The following creators have showcased Smörgåsbord:

Creator	Platform	Series
Coming Soon	YouTube	Coming Soon

If you've created content featuring Smörgåsbord, feel free to share it in the Discord community.

---

10. Thank You

Whether you're streaming, creating Let's Plays, recording tutorials, or making cinematic screenshots, thank you for helping showcase the incredible work of the 7 Days to Die modding community.

Your support helps new players discover Smörgåsbord and the talented mod authors whose work makes it possible.
