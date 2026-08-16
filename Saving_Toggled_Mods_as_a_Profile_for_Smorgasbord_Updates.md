# Saving Your Enabled & Disabled Mods for Future Smorgasbord Updates

When updating Smorgasbord, Mod Organizer 2 (MO2) can overwrite your current profile settings.

If you have:
- Enabled extra mods
- Disabled mods you do not want
- Customized your setup

...you should create a backup profile before updating.

This only takes about a minute and prevents you from having to redo all of your mod toggles after every update.

---

# Why This Matters

MO2 stores your enabled and disabled mod selections inside your Profile.

If you update Smorgasbord using the default profile, your custom mod setup may be reset.

Creating a separate backup profile with the `[NoDelete]` tag protects your personal setup during future updates.

---

# Step-by-Step Instructions

## 1. Open the Profile Menu in MO2

At the top of MO2, locate the **Profile dropdown menu**.

Click the dropdown arrow, then select:

**Manage...**

---

## 2. Copy Your Current Profile

Inside the Profile Manager:

1. Select the profile you currently use
2. Click **Copy**
3. Enter a new profile name

---

## 3. Add the `[NoDelete]` Tag

When naming the copied profile, place `[NoDelete]` at the beginning of the name.

Example:

```text
[NoDelete]CoolGuy24 List
```

You can replace `CoolGuy24` with your own username or preferred profile name.

---

# Important

Do NOT overwrite an existing profile.

Always create a new copied profile with a unique name.

---

# Result

After updating Smorgasbord:

- Your custom enabled/disabled mods will still be saved
- Your personal setup will remain intact
- You will not need to manually retoggle mods again

---

# Quick Summary

```text
Profile Dropdown → Manage → Copy Profile → Rename with [NoDelete]
```

---

# Example Images


<img width="2276" height="752" alt="image" src="https://github.com/user-attachments/assets/c6ec4b13-aa63-4f9c-a615-c54b0d91be8c" />


<img width="948" height="696" alt="image" src="https://github.com/user-attachments/assets/188dd310-0ad8-4f04-a89c-30d0938fa120" />

---

# Important After Future Smorgasbord Updates

If you created your new Profile using the `[NoDelete]` tag, any *new mods* added in future Smorgasbord updates will appear at the **bottom of MO2** inside that Profile.

You will need to:

1. Locate the newly added mods at the bottom of the left pane in MO2
2. Drag them into the appropriate Separator category
3. Place them where you want them within the mod list
4. Toggle the new mods as you like.

This is normal behavior and helps preserve your custom Profile setup during updates.

---

## 📋 How to Share & Import MO2 Profiles

Want to share your exact **enabled/disabled mod setup** with another Smörgåsbord user?

This can be useful for:

* 🎮 Multiplayer groups that want matching mods
* 📺 Streamers sharing their setup with viewers
* 👥 Friends who want the same playthrough experience

### ⚠️ Before You Start

Both users should have the **same Smörgåsbord revision installed**.

For example, if the Exporter is using **Revision 3.1.1.41**, the Importer should also be using **3.1.1.41**.

This process **does not download or install mods**. It simply tells MO2 which already-installed mods should be **enabled or disabled**.

---

### 📤 EXPORTER — Sharing Your Profile

1. Create/select the MO2 Profile you want to share.
2. Enable and disable your desired mods.
3. Open your MO2 installation folder.
4. Open:
   **`profiles → Your Profile Name`**
5. Find **`modlist.txt`**.
6. Copy that file and share it with the other user.

That's it!

---

### 📥 IMPORTER — Using the Shared Profile

1. Make sure you're using the **same Smörgåsbord revision** as the Exporter.
2. Open MO2.
3. Create a **NEW Profile**.
4. Give it a recognizable name.
5. **Close MO2.**
6. Open your MO2 installation folder.
7. Open:
   **`profiles → Your New Profile Name`**
8. Replace the existing **`modlist.txt`** with the one you received.
9. Launch MO2 again.
10. Select your new Profile.

MO2 should now show the same mods **enabled and disabled** as the Exporter's Profile.

---

### 🧪 Example

Streamer **CoolGuy84** creates:

**`CoolGuy84_Plays_Smorg`**

He configures his mods and shares:

**`modlist.txt`**

Viewer **Slappy77**:

**Creates `CoolGuy84_Plays_Smorg` Profile → Closes MO2 → Replaces its `modlist.txt` → Restarts MO2 → Selects the Profile**

Slappy77 should now have the same enabled/disabled mod configuration as CoolGuy84.

---

### 💡 Important

**Do NOT overwrite the default Smörgåsbord Profile.**

Always create a **new Profile** for imported configurations. This keeps the original Smörgåsbord setup available for troubleshooting or switching back to the default configuration.
