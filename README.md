# OniPlayer
## Fish memory? 200 episodes?
#### A C# console app that remembers your last watched video In Any Folders and plays.<br>One key, no thinking.

---

## What it actually does

You have Course or Anime folders With many Episodes.  
You don’t remember which one you watched last.  
**OniPlayer** Uses Windows Accses time And Playes The last Video/Anime Episode you Watched or Next one.

- Press **Enter** → it plays the last video you watched or Next one (you can change this in Play Mode Options).  
- Press **→** (right arrow) → it switches to “Play Next/Play current”. Then Enter plays the next video instead.

That’s the whole idea. No setup, no config, no remembering.

---

<img width="1104" height="639" alt="image" src="https://github.com/user-attachments/assets/4143b610-714c-4409-92a7-a4b976f5e5d8" />

---

## Why you might want it

- You learn in batches and hate the “what did I watch?” guessing game.  
- You have multiple courses, series, or workout videos spread across different folders.  
- You want a tool that’s portable, keyboard‑only, and doesn’t require 47 clicks.  
- You enjoy software that roasts you a little bit.

---

## How to Use (the essentials)

1. Put `OniPlayer.exe` in a folder (e.g. `D:\Tools\OniPlayer`).
2. Run it – it creates the config files automatically.
3. Add a video folder (press `1`) and give it a nickname.
4. Use **↑/↓** to choose a folder, **Enter** to play.
5. Press **→** on a folder to highlight `Play Next` / `Play Current`, then Enter to play that mode.
6. Change the global play mode by pressing `5` or navigating to “Play Mode”.
7. Exit with `Esc` – everything is saved.

> ⚠ Keep the config files beside the .exe. Just make a shortcut to the .exe if you want it on your desktop.

---

## Requirements & Note

- Windows 7 or later
- .NET Framework 4.7.2 (usually preinstalled)
- If `LastAccessTime` isn’t updating (rare), run once as admin:  
  `fsutil behavior set disablelastaccess 0` and restart.

---

## Build from source
Open in Visual Studio → Build. Or download the latest Release .exe from the [Releases page](https://github.com/SobieArts/OniPlayer/releases).

---

*“I binged a 120‑episode course with a fish memory and never once had to wonder where I left off. OniPlayer just… knows.”*
