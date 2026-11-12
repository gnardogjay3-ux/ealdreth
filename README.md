# Ealdreth

A co-op, top-down fantasy delve played with friends online, with an **AI dungeon master**.
A city above, wild country and a sea around it, and a vast dungeon below. Explore freely and
the world reacts; fights are turn-based (or live, if you like) under the 2024 5th-edition rules.

This page is where the game is downloaded. **Windows 10/11 (64-bit)**, about 4 GB of free space.

---

## Get the game (first time)

1. Open **[Releases](../../releases)** and find the newest release marked **Full game**.
2. Download these 4 files into **one folder**:
   - `Ealdreth.part1`, `Ealdreth.part2`, `Ealdreth.part3`
   - `Put the game together.bat`
3. Double-click **Put the game together.bat** and wait until it says **Done!** (about a minute).
   Windows may warn you about the script — click **More info → Run anyway**.
4. Double-click **Ealdreth.exe** to play. You can delete the three part files afterwards.

The first time you run it Windows may say *"Windows protected your PC"* — the game isn't
code-signed. Click **More info → Run anyway**.

## Updates (patches)

Most updates are one small file, like `ealdreth_1.0.1.pck`.

1. Next to **Ealdreth.exe**, make a folder called **`patches`** (once).
2. Download the newest **Patch** release's `.pck` file into it.
3. Start the game: the main menu shows the version, e.g. **v1.0.1 (patched)**.

Each patch holds every change since its full game, so only the newest one is needed.
When a new **Full game** release comes out, get that instead (and empty the `patches` folder).

## Playing together

Everyone needs **the same version** — the game tells you if you don't match.

- **Host:** open the game, type your name, leave the port at 7777 and click **Host a game**.
  To let friends in over the internet without touching your router, a free tunnel such as
  [playit.gg](https://playit.gg) (a **UDP** tunnel to local port 7777) or
  [Tailscale](https://tailscale.com) works well.
- **Join:** type your name, the host's address and port, and click **Join a game**.
- In the lobby, bring your own hero (**Bring a hero…** / **Create a hero**) or take one of the
  host's. Heroes nobody takes are played by the AI.

The host's AI dungeon master and ElevenLabs voices (if they've set them up with their own keys)
are shared with everyone who joins; keys never leave the host's computer.

---

## Credits and licences

Ealdreth's world, places, people, story, maps, art and code are its own. It is an unofficial,
non-commercial fan project and isn't affiliated with or endorsed by Wizards of the Coast.

Rules content comes from open-licensed 5th-edition material: the **System Reference Document
5.2** and **5.1** by Wizards of the Coast LLC (CC-BY-4.0), and monsters, magic items and spells
from other open-licensed books (Kobold Press's Black Flag SRD, Tome of Beasts 1–3 and Creature
Codex; EN Publishing's Level Up; and others) under CC-BY-4.0 and the Open Game License v1.0a.
Full attributions and the licence texts are in **[LICENSES.md](LICENSES.md)**.

Fonts: Cinzel and Alegreya Sans (SIL Open Font License 1.1). Built with [Godot](https://godotengine.org).
