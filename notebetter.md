---
layout: default
display: Better <strong>Note Blocks</strong>
mobile: Better Note Blocks <small>NoteBetter</small>
---
##About
NoteBetter adds a configuration file for Note Blocks, letting you:

- Specify custom instruments, either for a block or for a block category!
- Override vanilla instruments!
- Set a volume to be used for each instrument!

##Format
The configuration file is a JSON which looks like this:

    {
      "blocks": [
        {
          "block": "minecraft:stone",
          "sound": {
            "name": "minecraft:note.bd",
            "volume": 3.0
          }
        }
      ],
      "materials": [
        {
          "material": "minecraft:stone",
          "sound": {
            "name": "minecraft:note.bd",
            "volume": 3.0
          }
        }
      ],
      "default": {
        "name": "minecraft:note.harp",
        "volume": 3.0
      }
    }

The full documentation of the format used is available [on the wiki](https://github.com/eNByeX/NoteBetter/wiki/Format).

On the first run, NoteBetter will install some examples in the configuration directory.

##Installing
NoteBetter is a Forge mod. To install NoteBetter, first [install Forge](http://www.minecraftforge.net/wiki/Installation/Universal),
then drop the NoteBetter jar in the mods folder.

##Downloads
Downloads are available from [CurseForge](http://minecraft.curseforge.com/projects/notebetter) and [GitHub](https://github.com/eNByeX/NoteBetter/releases).