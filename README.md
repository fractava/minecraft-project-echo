# Project Echo

This project packages [Project Echo](https://gitlab.com/alwus/project-echo) for use in MultiMC using [Modsman](https://github.com/sargunv/modsman/) to download the mods from CurseForge instead of distributing them directly.

This example pack consists of all the mods and their dependencies. Import this URL into MultiMC to check it out for yourself:

```
https://github.com/fractava/minecraft-project-echo/archive/master.zip
```

## Setup

1. Download the modpack zip
2. Import the modpack zip into MultiMC
3. Launch the game
4. On first run, the included prelaunch script will download modsman-packutil and invoke it to download mods and resource packs from CurseForge
5. On subsequent runs, Modsman will NOT be invoked again, just like a regular pack
