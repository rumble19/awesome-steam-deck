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
- [BIOS Undervolt](https://youtu.be/Roi6lvrcH-I?si=Q8nvUFDA5klv1oUl&t=57) - As of SteamOS 3.5, Valve officially added options so you can now undervolt your deck from the BIOS easily. You stand to gain a small performance boost and improve your battery life by pushing your undervolt as far as you can. Pushing it too far can result in instability, however. Each deck is different, so you will have to experiment to find what works for your particular chip. I have mine set to -30mv across the three options. The linked video has pretty clear instructions but you can boot to the BIOS by **holding the volume up button while powering on the deck**. If you push the undervolt too far and your deck wont boot, you can reset the CMOS by holding down the **Volume Down button, 3 dot button, and power button** while powering on the deck, which will reset all your BIOS settings to stock and let the deck boot normally. Note the linked video is from when SteamOS 3.5 was in beta, but since it has been released to the stable channel, you don't need to switch your deck to the beta or preview channels to access these new BIOS options.


## Decky Loader and Recommended Plugins
- [Decky Loader](https://github.com/SteamDeckHomebrew/decky-loader) - Adds a plugin store and menu items in the quick access menu to increase functionality and customizability of SteamOS. Once installed, I consider the following as must have plugins:
    - **Pause Games** - Lets you suspend games while the deck is still on. An option to 'pause games on sleep' generally increases compatibility with games that otherwise are finicky resuming from the deck's sleep mode.
    - **ProtonDB Badges** - Adds a badge and a link to ProtonDB for each game in your library. 
    - **SteamGridDB** - Add, find, and change grid artwork from the built-in steam menu. 
    - **CSS Loader** - Skin SteamOS with all kinds of community made themes and tweaks.
    - **HLTB** - Adds estimated completion times to your library. 
    - **Animation Changer** - Add, find, and randomly display custom boot videos made by the community.
    - **AutoFlatpak** - A handy way to keep your installed flatpaks up-to-date without having to jump over to Desktop mode. 

## Emulation
- [Emudeck](https://www.emudeck.com) - Installs a whole bunch emulators automatically and sets up a nice folder structure to keeps your roms and saves organized. 
- [RetroDECK](https://retrodeck.net/) - An alternative to Emudeck that you can find on the Discover store, installs the same emulators as Emudeck, but all within a single flatpak. A bit of a philosophical difference between the two projects. Emudeck is probably more popular, but you can decide for yourself. 

## Utilities
- [Enable SSHD and SSHFS](https://www.youtube.com/watch?v=6GT67H8Xsjs) - the easiest way to transfer files to and from your Deck from another computer.
- [Xone Installer](https://gist.github.com/SavageCore/263a3413532bc181c9bb215c8fe6c30d) - A script to enable support for the 2.4ghz dongle for Xbox One controllers. Enables you to wake the deck up from sleep with the controller as well. This will need to be rerun after steam updates, but the script has a convenient desktop shortcut included.
- [Shortix](https://github.com/Jannomag/shortix) - A script that creates human readable symlinks for Proton game prefixes. 
- [NonSteamLaunchers](https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck) - Automatic installation of the most popular third-party launchers.
- [XBPlay](https://store.steampowered.com/app/2693120/XBPlay/) - The only non-free recommendation on this list. A great way to stream your Xbox One or Series X/S locally to your Deck, or from the cloud with a subscription to xCloud. Now available directly through Steam. [Greenlight](https://github.com/unknownskl/greenlight) is a free alternative, but I had a better experience with XBPlay.
  
## From Discover
Apps to install from the built-in Discover store from Desktop Mode.
- **ProtonUp-QT** - Install and manage custom (GE) Proton builds. Handy for games that don't work with the default Proton version for whatever reason. 
- **ProtonTricks** - Very useful tool to manage finicky games that require extra tweaks to run correctly. This can help with a bunch of mod installers as well. Lets you right-click an exe and run it in an game prefix.
- **Anydesk** - Easy, free, and cross-platform remote desktop software. I do most of my Deck setup and management from my PC using Anydesk.
- **Moonlight** - Stream games from your PC to your Deck. Useful for AAA games that don't run well on the Deck. Need to set up Nvidia Gamestream or [Sunshine](https://github.com/LizardByte/Sunshine) on your PC first.
- **Chiaki** - Stream your PS4 or PS5 locally to your Deck.
- **SyncthingGTK** - Seamlessly keep a folder in sync between your Deck and another computer. I use this to keep emulator saves in sync from my Deck to my PC.
- **Heroic Launcher** - Alternative launcher for Epic Games Store and GOG. Allows you to sign in and install games from either library. 

    
## Cool Projects
Strictly optional, interest dependant projects that I just think are cool. Maybe you will too!
- [Ship of Harkinian](https://www.shipofharkinian.com/) - A native port of Zelda: Occarina of Time. Runs in native resolutions, 60fps+, with a ton of quality of life improvements and a built-in randomizer.
- [Bloodborne PSX](https://b0tster.itch.io/bbpsx) - An incredibly imaginative demake of Bloodborne in the style of a PS1 game. Runs perfect on the Deck. 
- [Apotris](https://akouzoukos.com/apotris) - A modern take on Tetris with a ton of modes and options packaged as a Gameboy Advance rom. Currently, you'll need to install an emulator to run it, see the [emulation](#emulation) section above.
- [Sunshine](https://github.com/LizardByte/Sunshine) - A free alternative to Nvidia GameStream for streaming games from your PC to your Deck. Works with AMD as well as Nvidia GPUs.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
