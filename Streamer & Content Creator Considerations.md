# 🎥 Streamer & Content Creator Considerations

This page contains tips and recommendations for streamers, YouTubers, screenshot artists, and other content creators using Smörgåsbord.

If you are streaming/recording using Smorgasbord, feel free to reach out to me in a DM on Discord for assistance as needed.  

---

## Table of Contents

## 📸 1. Screenshots

* [Built-In Screenshots (F9)](#11-built-in-screenshots-f9)
* [NVIDIA Screenshots (Alt+F1)](#12-nvidia-screenshots-altf1)

## 🎬 2. Recording & Streaming

* [OBS Recommendations](#21-obs-recommendations)

## ⚙️ 3. Performance Considerations

* [Performance Considerations](#31-performance-considerations)

## 🎨 4. Thumbnail Creation Tips

* [Useful Console Commands](#41-useful-console-commands)

## 🧟 5. Mod Considerations for Creators

* [Mod Considerations for Creators](#51-mod-considerations-for-creators)

## 6. Exporting Your Custom Profile to share with Community Members

* [Exporting Your Custom Profile to share with Community Members](#61-exporting-your-custom-profile-to-share-with-community-members)

## 🤖 7. Twitch Chat Commands

* [Twitch Chat Commands](#71-twitch-chat-commands)

## 🎵 8. Music & Copyright

* [Music & Copyright](#81-music--copyright)

## ⭐ 9. Featured Content Creators

* [Featured Content Creators](#91-featured-content-creators)

## ❤️ 10. Thank You

* [Thank You](#101-thank-you)

---

## 1. Screenshots

Capturing high-quality screenshots is essential for thumbnails, social media posts, bug reports, and promotional content.

### 1.1 Built-In Screenshots (F9)

Normally most of you launch your game from Steam and use the F12 key to take screenshots.

Since we are launching the game from MO2 (and not Steam), the F12 key may not work correctly, so here is an easy workaround:

7 Days to Die includes a built-in screenshot function.

Default Key

F9

Screenshots are saved to:

%AppData%\Roaming\7DaysToDie\Screenshots

This is often the easiest and most reliable method when launching the game through Mod Organizer 2.

> [!TIP]
> If you are accustomed to using Steam's F12 screenshot functionality,
> 
> be aware that Steam Overlay may not always attach correctly when launching through MO2.
> 
> The built-in F9 screenshot key is generally the most reliable option.

### 1.2 NVIDIA Screenshots (Alt+F1)

For NVIDIA users:

Alt + F1
Advantages
Full-resolution screenshots
Independent of Steam Overlay
Reliable with Mod Organizer 2

---

## 🎬 2. Recording & Streaming

### 2.1 OBS Recommendations

For most users:

- Game Capture

provides the best performance.

Alternative methods:

- Window Capture
- Display Capture

## ⚙️ 3. Performance Considerations

### 3.1 Performance Considerations

Please see the Performance Optimization Guide for mod selection and setting recommendations:

➡ **[Performance_Optimization.md](Performance_Optimization.md)**

When using a heavy Mod List like Smörgåsbord together with OBS, it is normal for the game to stutter for the first few minutes after loading into a world.

On most systems, this should settle down after 2-3 minutes.

If recording or streaming causes performance issues, consider reducing:

- Shadow Distance
- Reflection Quality
- Water Quality
- Dynamic Mesh Distance
- Dynamic Resolution

These settings generally provide the largest performance gains with minimal visual impact during gameplay recordings.

---

## 🎨 4. Thumbnail Creation Tips

Creating thumbnails often requires screenshots that are difficult to capture during normal gameplay.

### 4.1 Useful Console Commands

Enable Debug Menu

_dm_

Enable God Mode

_god_

Enable Fly Mode

_fly_

Toggle HUD

**F7**

Pause Time

_st_

These commands can help stage screenshots and cinematic scenes.

---

## 🧟 5. Mod Considerations for Creators

### 5.1 Mod Considerations for Creators

Smörgåsbord intentionally adds:

- More zombie variety
- Expanded clothing, armor, vehicle, décor, and weapon variety
- Additional points of interest
- Additional ambient encounters

As a result:

Gameplay footage may differ from vanilla.

Screenshots may contain content unfamiliar to viewers.

Unique encounters can occur that are not present in a standard game.

This is normal and expected behavior.



> [!CAUTION]
> I strongly recommend running a brief test game with the mods you selected before committing to a stream or long-format playthrough.
> 
> This gives you time to determine whether you enjoy a particular mod before building content around it.
> 
> Some mods can be toggled mid-save. Others cannot.
> 
> The default Smörgåsbord Profile in MO2 was built with streamers in mind, but it is still worth running a test game and tailoring the experience to your audience.

--
### Byteblazar's Screamers

This mod causes Screamers to move at extremely high speed and attempt to flee from the player.

Since they do not stop screaming, this can become audibly annoying for your audience.

This mod is disabled by default, and I encourage you to leave it disabled while streaming.

--
### WalkerSim is Intentionally Challenging

If WalkerSim is too difficult for your preferred content style, you can reduce the Zombie Population Density value in the WalkerSim.xml file.

140 is a good balance for most players.
192 is what I personally use for a more intense experience.

You can safely edit, disable, or enable WalkerSim mid-save.

It is save-safe to do so.

--
### EFTX

The default list includes hundreds of additional ammunition types.

If this feels like unnecessary inventory management for your content, you can disable the current Z2 ammo option and select one of the Vanilla Z2 alternatives.

For guidance:

➡ [EFTX_for_Dummies.md](EFTX_for_Dummies.md)

--
### Peek Lean

Either disable this mod or remap the controls.

You can:

Disable it in MO2
Rebind the keys in the in-game Mods (Gears) menu

This can prevent conflicts with your existing control scheme.

--

### Ultra-Dark-Night mods & Medical Conditions

I strongly discourage using these mods for a stream.

These mods are disabled by default.

While they can be immersive for personal gameplay, they generally create a poor viewing experience.


### Medical Conditions

Adds vision-related ailments that can introduce effects such as:

- Blurred vision
- Visual impairment effects


### Ultra-Dark-Night

Makes nighttime significantly darker.

Potential issues:

- Viewers cannot see what is happening
- Driving becomes difficult to watch
- Important gameplay moments become visually unclear

--

### Better Biomes, NPC-CORE, CATUI & Other Heavy Mods

Even if you are using high-end hardware, heavy mods combined with Smörgåsbord and OBS can become extremely resource intensive.

I generally do not recommend using multiple heavy mods while recording or streaming.

Please refer to: Mod Considerations section of the ➡ **[Performance_Optimization.md](Performance_Optimization.md)**

---

## Adding Your Own Mods

I have helped streamers add:

- Additional décor mods
- Community member zombie-name mods
- Small quality-of-life additions

Most lightweight mods can be added to MO2 without issue.

These are reasonable accommodations, and I am usually willing to help content creators customize their experience.

That said, keep expectations reasonable.

I am good, but I am not a miracle worker. I cannot magically make Darkness Falls + Rebirth + Smörgåsbord coexist in perfect harmony. 😄

For guidance:

➡ [ADDING_YOUR_OWN_MODS.md](ADDING_YOUR_OWN_MODS.md)


> [!TIP]
> Make a personalized copy of the Smörgåsbord Profile in MO2 for your own use.
> 
> This allows your toggled/added mods to remain in MO2 after updating the list in Wabbajack.
> 
> It also allows you to share your customized list with users.

Give it your name and place [NoDelete] at the beginning.

Also place [NoDelete] in front of any added mods.

This ensures your changes survive future Smörgåsbord updates.

It is generally best not to update or toggle mods mid-save.

Some updates are harmless. Others are not.

Make backups and keep notes regarding any changes you make.

For detailed instructions:

➡ [Saving_Toggled_Mods_as_a_Profile_for_Smorgasbord_Updates.md](Saving_Toggled_Mods_as_a_Profile_for_Smorgasbord_Updates.md)

---

## 📤 6. Exporting Your Custom Profile to Share with Community Members

### 6.1 Exporting Your Custom Profile to Share with Community Members

One of the advantages of MO2 is that you can export your customized setup and share it with viewers, friends, or community members.

To export your customized list, in MO2, right-click a mod on the left half of the screen, press All Mods, Export to csv


<img width="1340" height="1480" alt="image" src="https://github.com/user-attachments/assets/abd712a9-4f60-4ca0-a49d-bca93ea8d7c8" />


Toggle which columns you'd like to include in the csv.


<img width="1312" height="1150" alt="image" src="https://github.com/user-attachments/assets/e1f327f5-be8c-4659-af5c-a88ac043d436" />


Hit Ok, and Save as.  


<img width="1260" height="1208" alt="image" src="https://github.com/user-attachments/assets/99d591f0-57c6-4c18-836e-b7feeabfed63" />

_The "+" sign means the mod is enabled (toggled on), and the "-" sign means the mod is disabled (toggled off) in your Profile._


This is particularly useful if:

- You stream with a customized Smörgåsbord setup
- Viewers frequently ask for your exact mod configuration
- You want others to replicate your experience
- Recommended Process
- Create a dedicated profile for your playthrough.
- Place [NoDelete] in front of the Profile name.
- Enable or disable mods as desired.
- Test the profile thoroughly.
- Export the profile's mod list.
- Upload the resulting file to GitHub, Discord, Google Drive, or another file-sharing service.

You can then reference that exported list through your Twitch bot, YouTube descriptions, Discord server, or social media posts.

This allows viewers to see exactly which options you selected from the larger Smörgåsbord collection.

---

## 🤖 7. Twitch Chat Commands

### 7.1 Twitch Chat Commands

If you're streaming Smörgåsbord, viewers will often ask:

_What mods are you using?

Is this an overhaul mod?

How do I install it?

Where can I download it?_

Creating a simple Twitch chat command can save a tremendous amount of time during a stream.

--

### !mods Command

Recommended Nightbot, StreamElements, or Streamer.bot command:

Here is the list of mods included for you to select in the Smörgåsbord Mod List: https://www.nexusmods.com/games/7daystodie/collections/3olqbw/mods

Short Version

Smörgåsbord Mod List: https://www.nexusmods.com/games/7daystodie/collections/3olqbw

--

## Suggested Additional Commands

### !smorgasbord ("What is Smorgasbord?)
Smörgåsbord answers the question: "What if vanilla 7 Days to Die had ten years of community improvements layered onto it?" Download: https://www.nexusmods.com/games/7daystodie/collections/3olqbw

### !modlist
Want the same mods I'm using? Check out my custom Smörgåsbord Profile:

_Add a link to your exported profile here._

### !discord
Need help installing or troubleshooting Smörgåsbord? Visit the GitHub page: https://github.com/Fluffernuttersandwich/Smorgasbord/blob/main/README.md

--

## 💡 Creator Tip

Viewers frequently discover Smörgåsbord through Twitch streams and YouTube videos.

Adding a simple !mods command allows interested viewers to quickly find the collection without interrupting gameplay or requiring repeated explanations.

This is especially useful during:

- Horde Nights
- Challenge Runs
- Community Events
- Large Viewer Counts

---

## 🎵 8. Music & Copyright

### 8.1 Music & Copyright

The default Smörgåsbord Mod List itself does not use copyrighted music.

Shameless Plug: **Stormwrought Audio**

All music used in my own recent recordings comes from my royalty-free music channel:

https://www.youtube.com/@StormwroughtAudio

You are welcome to use the music for:

- YouTube videos
- Twitch streams
- Mod showcases
- Gameplay content

The music is royalty-free, creator-friendly, and stream-safe.

---

## ⭐ 9. Featured Content Creators

### 9.1 Featured Content Creators

The following creators have showcased Smörgåsbord.

## 📺 YouTube

| Creator | Channel |
|----------|----------|
| Fin (FNS) | https://www.youtube.com/@Fin-FNS |

## 🎮 Twitch

| Creator | Channel |
|----------|----------|
| Joutre | https://www.twitch.tv/joutre_ |
| Rosencrantz | https://www.twitch.tv/rosencrantz_ttv |
| LexCPlays | https://www.twitch.tv/lexcplays |

---

## Interested in creating content featuring Smörgåsbord?

Join the community and share your videos, streams, screenshots, and highlights. We are always happy to support creators showcasing the modding community's work.

If you've created content featuring Smörgåsbord, feel free to share it in the Discord community.

I am always happy to support creators willing to showcase the incredible work of the 7 Days to Die modding community.

---

## ❤️ 10. Thank You

### 10.1 Thank You

Whether you're streaming, creating Let's Plays, recording tutorials, or making cinematic screenshots, thank you for helping showcase the incredible work of the 7 Days to Die modding community.


Your support helps new players discover Smörgåsbord and the talented mod authors whose work makes it possible.
