<!-- omit from toc -->
# Awesome Steam Deck [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> This is not a complete guide on everything cool that you can do with your Steam Deck, but it is how I have mine set up. I will try to keep it updated as I find new and/or better projects. Let me know if you think I've made an error or if you have a suggestion for something to add. Each section of this list is roughly sorted in order of importance (must-have -> optional).


## Contents
- [Contents](#contents)
- [Performance Tweaks](#performance-tweaks)
- [Decky Loader and Recommended Plugins](#decky-loader-and-recommended-plugins)
- [Emulation](#emulation)
- [Utilities](#utilities)
- [From Discover](#from-discover)
- [Cool Projects](#cool-projects)
- [Contribute](#contribute)



## Performance Tweaks
- [Cryoutilities](https://github.com/CryoByte33/steam-deck-utilities) - Gain a small performance boost in most games. 
- [BIOS Undervolt]() - As of SteamOS 3.5, you can now undervolt your deck from the BIOS easily. You can gain a small performance boost and improve your battery life by pushing your undervolt as far as you can while maintaining stability. Each deck is different, so you will have to experiment to find what works for your deck. I have mine set to -30mv across the three options. No link for this one but you can boot to the BIOS by **holding the volume up button while powering on the deck**. If you push it too far and can't boot your deck, you can reset the CMOS by holding down the **Volume Down button, 3 dot button, and power button** while powering on the deck, which will reset all your BIOS settings and let the deck boot normally. 


## Decky Loader and Recommended Plugins
- [Decky Loader](https://github.com/SteamDeckHomebrew/decky-loader) - Adds a plugin store and menu items in the quick access menu to increase functionality and customizability of SteamOS. Once installed, I consider the following as must have plugins:
    - **Pause Games** - Lets you suspend games while the deck is still on. Generally increases compatibility with games that are finicky on sleep.
    - **CSS Loader** - Skin SteamOS with all kinds of community made themes and tweaks.
    - **HLTB** - Adds estimated completion times to your library. 
    - **SteamGridDB** - Add, find, and change grid artwork from the built-in steam menu. 
    - **Animation Changer** - Add, find, and randomly display custom boot videos made by the community. 
    - **ProtonDB Badges** - Adds a badge and a link to ProtonDB for each game in your library. 
    - **AutoFlatpak** - A handy way to keep your installed flatpaks up-to-date without having to jump over to Desktop mode. 

## Emulation
- [Emudeck](https://www.emudeck.com) - Installs all of the emulators automatically and sets up a nice folder structure to keeps your roms and saves organized. 
- [RetroDECK](https://www.emudeck.com) - An alternative to Emudeck that you can find on the Discover store, installs the same emulators as Emudeck, but all within a single flatpak. A bit of a philosophical difference between the two projects.

## Utilities
- [Enable SSHD and SSHFS](https://www.youtube.com/watch?v=6GT67H8Xsjs) - the easiest way to transfer files to and from your Deck from another computer.
- [Xone Installer](https://gist.github.com/cdleveille/e84c235c6e8c17042d35a7c0d92cdc96) - A script to enable support for the 2.4ghz dongle for Xbox One controllers. Enables you to wake the deck up from sleep with the controller as well. This will need to be rerun after steam updates, but the script has a convenient desktop shortcut included.
- [Shortix](https://github.com/Jannomag/shortix) - A script that creates human readable symlinks for Proton game prefixes. 
- [NonSteamLaunchers](https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck) - Automatic installation of the most popular third-party launchers.
  
## From Discover
Apps to install from the built-in Discover store from Desktop Mode.

- **ProtonUp-QT** - Install and manage custom Proton builds. Handy for games that don't work with the default Proton version. 
- **ProtonTricks** - Very useful tool to manage finicky games that require extra tweaks to run correctly. Lets you right-click an exe and run it in an game prefix.
- **Anydesk** - Easy, free, and cross-platform remote desktop software.
- **Moonlight** - Stream games from your PC to your Deck. Useful for games that don't run well on the Deck. Need to set up Nvidia Gamestream or [Sunshine](https://github.com/LizardByte/Sunshine) on your PC first.
- **xbPlay** - The only non-free recommendation on this list. A great way to stream your Xbox One or Series X/S locally to your Deck. [Greenlight](https://github.com/unknownskl/greenlight) is a free alternative, but I had a better experience with xbPlay.
- **Chiaki** - Stream your PS4 or PS5 locally to your Deck.
- **SyncthingGTK** - Seamlessly keep a folder in sync between your Deck and another computer. I use this to keep emulator saves in sync from my Deck to my PC.
- **Heroic Launcher** - Alternative launcher for Epic Games Store and GOG. Allows you to sign in and install games from either library. 

    
## Cool Projects
Strictly optional, interest dependant projects that I just think are cool. Maybe you will too!
- [Ship of Harkinian](https://www.shipofharkinian.com/) - A native port of Zelda: Occarina of Time. Runs in native resolutions, 60fps+, with a ton of quality of life improvements and a built-in randomizer.
- [Bloodborne PSX](https://b0tster.itch.io/bbpsx) - An incredibly imaginative demake of Bloodborne in the style of a PS1 game. Runs perfect on the Deck. 
- [Apotris](https://akouzoukos.com/apotris) - A modern take on Tetris with a ton of modes and options packaged as a Gameboy Advance rom. 
- [Sunshine](https://github.com/LizardByte/Sunshine) - A free alternative to Nvidia GameStream for streaming games from your PC to your Deck. Works with AMD as well as Nvidia GPUs.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
