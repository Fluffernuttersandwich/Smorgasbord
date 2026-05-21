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



