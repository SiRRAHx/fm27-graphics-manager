<p align="center">
  <img src="icon.png" width="96" alt="">
</p>

<h1 align="center">FM27 Graphics Manager</h1>

<p align="center">
  A free Windows app that downloads, installs, updates and removes faces, logos and kits for <b>Football Manager 27</b>, so you don't have to unzip, copy and fix folders by hand.
</p>

<p align="center">
  <a href="https://github.com/SiRRAHx/fm27-graphics-manager/releases/latest"><b>⬇ Download the latest version</b></a>
</p>

---

## What it does

- **One place for your graphics packs.** Browse popular face, logo and kit packs, install them with one click and remove them just as easily.
- **Puts everything in the right folder.** Packs are unpacked, wrapper folders are stripped and the files land in `Documents\Sports Interactive\Football Manager 27\graphics`, where FM27 expects them.
- **Keeps packs up to date.** It checks the pack sites for new versions and shows an **Update** button. Monthly update files can be added on top of a pack you already have.
- **Skips duplicate faces.** If a player's face is already in another pack, it can be left out, so packs don't fight over the same player.
- **Check my setup.** Finds and fixes the usual reasons graphics don't show in game.
- **See what you have.** **My packs** shows how much space each pack uses, and **Scan for packs** finds ones you installed yourself.
- **Downloads in the background.** Close the window and downloads carry on, with a notification when they finish.
- **Back up and restore** your packs and settings, for example when moving to a new PC.
- **Add any pack** by pasting a link to its page.
- **Themes.** Pick a colour theme and background in Settings → Appearance.
- **Updates itself.** The app tells you when a new version is out and installs it for you.

The pack list is updated online, so new packs appear without needing an app update.

## Install

1. Download `FM27-Graphics-Manager-Setup-<version>.exe` from the [latest release](https://github.com/SiRRAHx/fm27-graphics-manager/releases/latest).
2. Run it. Windows may show **"Windows protected your PC"** because the app isn't code-signed: click **More info → Run anyway**.
3. Choose where to install and which shortcuts you'd like. No admin rights are needed.

The first time it opens, the app asks for:

- a **downloads folder**, where pack archives are saved and kept, and
- your **Football Manager 27 folder**, usually `Documents\Sports Interactive\Football Manager 27`.

Both can be changed later in Settings.

> **On version 1.0.0?** That version closes with a JavaScript error when it starts, so it can't update itself. Download and run the latest installer once; it updates your install and keeps your packs and settings.

## Getting packs

- Press **Download & install** on a pack in **Browse**. Packs with a direct link download straight away.
- Packs that are only on the creator's site (for example ones that need a sign-in) open that page in a window inside the app. Sign in if asked and press the site's download button; the app catches the file and installs it.
- Already downloaded a pack in your browser? Use **⋯ → Install from file…** on its card.
- `.zip` and `.7z` work out of the box. `.rar` packs need [7-Zip](https://7-zip.org) installed.

The app only ever deletes a pack's own folder inside `graphics`. If a folder with the same name is already there and the app didn't install it, it's renamed to `<name>.backup-<date>` rather than overwritten.

## Faces not showing in game?

1. Close FM27 completely and start it again. It only loads new graphics when it starts.
2. Run **Check my setup** in the app.
3. In **My packs**, make sure the pack has no warnings (such as a missing `config.xml`), and use **Open folder** to check the images are in your `graphics` folder.

## Problems or ideas

In the app, go to **Settings → Copy problem report**, then press **Report on GitHub** and paste it into a [new issue](https://github.com/SiRRAHx/fm27-graphics-manager/issues).

## Credits

All graphics packs belong to their creators. The app only downloads them from where the creators publish them, so please support those sites.

FM27 Graphics Manager is a free fan-made tool. It isn't made by, or affiliated with, Sports Interactive or SEGA. Football Manager is a trademark of Sports Interactive.
