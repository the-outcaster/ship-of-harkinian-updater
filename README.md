# Ship of Harkinian Updater for Steam Deck/Linux
Ship of Harkinian (*Zelda: OoT* PC port) installer and updater for Steam Deck/Linux.

![Screenshot](https://i.imgur.com/jFRIL7L.png)

Download, update, and play SoH. It was primarily designed to be used with the Steam Deck but it should also work with pretty much any other distro, so long as it has `p7zip-full` installed (for installing OoT Reloaded). You can also view the SoH changelog, install a couple of Steam Deck-specific mods, install high-resolution textures, and add the game as a non-Steam shortcut.

This script assumes you have a legally-dumped ISO of *Zelda: Collector's Edition* (PAL or AU) and stored somewhere on your device. Follow the instructions on [Wii.Guide](https://wii.guide/dump-games.html) for dumping your disc with a softmodded Wii.

If you're on Steam Deck, download the [desktop file](https://raw.githubusercontent.com/linuxgamingcentral/ship-of-harkinian-updater/main/soh-updater.desktop) (right-click, save link as...) and run it. Other distros can run the script with:

`curl -L https://raw.githubusercontent.com/linuxgamingcentral/ship-of-harkinian-updater/main/soh-updater.sh | sh`

## How to Use
1. Download SoH with the script. If there's an update, the script will overwrite the existing files (your save data and configuration files will still be intact).
2. Install the Dolphin emulator if you don't already have it installed. The script has an option here to easily install it.
3. Run Dolphin. Add your ISO filepath. Right-click the ISO, go to Properties -> Filesystem -> Extract `zelda_PAL_093003.tgc` under the "tgc" folder and place it in `~/Applications/ship-of-harkinian/`.
4. Extract the ROM from the TGC file with the script. It will take a few minutes.

From there, you can run SoH without having to re-do all of these steps.

See my [ROM dumping guide for Steam Deck](https://linuxgamingcentral.com/posts/ship-of-harkinian-steam-deck-guide/) if you need more help.

## Known Issues
- Adding SoH as a non-Steam shortcut can be hit or miss, you will likely need to manually add it.
