<p align="center">
  <img src="./program_info/polymc-header-black.svg#gh-light-mode-only" alt="PolyMC logo"/>
  <img src="./program_info/polymc-header.svg#gh-dark-mode-only" alt="PolyMC logo"/>
</p>
<br>

# Information

This fork is a _very_ small modification to the PolyMC Minecraft launcher that allows for offline accounts to be used without an existing premium account added to the launcher.

Some of the reasons I made this:
- Microsoft's decisions over Minecraft's account system which now forces players to create a Microsoft account to continue playing and most likely have their information collected then sold.
- Mojang's account moderation / deletion for wrongthink.
- Mojang's recent addition of Snooper to 1.18, an analytics reporter that Mojang promises to not misuse but probably will.

Please keep in mind that I do not support piracy because piracy is illegal and not allowed on GitHub. I just made this for those who own a premium account but do not want to authenticate with Microsoft servers to play the game.

Also know that because you are using an offline account, no server can be joined unless it is modified by the server owner to skip player verification. The most popular servers are not going to be playable.

# Compiling and Installing

Currently, there are no binary builds available. Compilation instructions for various systems are listed below.

### Arch / Manjaro / Arch-based

PolyMC-Cracked is available in the AUR as ```polymc-cracked-git```

### Any GNU/Linux
```
git clone --recursive https://github.com/catfromplan9/PolyMC-Cracked.git
cd PolyMC-Cracked

cmake -S . -B build -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX="/usr" -DENABLE_LTO=ON
cd build
make -j$(nproc) install # Run this as root
```

### Anything else

Build instructions for BSDs and proprietary privacy-invasive systems such as macOS and Windows can be found [here](https://polymc.org/wiki/development/build-instructions).

# What is PolyMC?

PolyMC is a custom launcher for Minecraft that focuses on predictability, long term stability and simplicity.

This is a **fork** of the MultiMC Launcher and not endorsed by MultiMC.
If you want to read about why PolyMC was created, check out [PolyMC's FAQ page](https://polymc.org/wiki/overview/faq/).
<br>

# Help & Support

Do not contact me for support. I do not maintain PolyMC, so I will not be able to help you with bug reports. If you're willing to write a fix for a crack related bug and make a pull request for it, I might accept it.

Send all bugs or technical questions to PolyMC through one of their communities:

[PolyMC Matrix Space](https://matrix.to/#/#polymc:matrix.org)

[PolyMC Discord](https://discord.gg/xq7fxrgtMP)

[r/PolyMCLauncher](https://www.reddit.com/r/PolyMCLauncher/)

## Forking/Redistributing/Custom builds policy

Do whatever you want, PolyMC doesn't care. Just follow the license. If you have any questions about this feel free to ask PolyMC in an [issue](https://github.com/PolyMC/PolyMC/issues).

All launcher code is available under the GPL-3.0-only license.

The logo and related assets are under the CC BY-SA 4.0 license.
