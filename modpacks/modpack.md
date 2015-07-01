### Description

List specific details for a modpack, including what mods are included.

### Endpoint

```GET /api/v1/modpack/$ID.json```

### Required Parameters

> ID = ID of the modpack you are requesting.

### Sample

**Request**

```GET https://www.modpackindex.com/api/v1/modpack/41.json```

**Result**

```
{
    "id": 41,
    "name": "Drone Pack",
    "deck": "A bee based Modpack. Explore worlds searching for bees. Collect bees and breed them to create new, better bees. Breeding is to much work? Then genetically modify bees to make them do anything. While on the hunt for bees you are being hunted.",
    "website": "http://forum.feed-the-beast.com/threads/1-7-10-drone-pack-bees-hqm-two-quest-routes-tech.52449/",
    "download_link": "http://www.feed-the-beast.com/#download",
    "donate_link": "http://forum.feed-the-beast.com/threads/1-7-10-drone-pack-bees-hqm-two-quest-routes-tech.52449/",
    "wiki_link": "",
    "description": "The Drone Pack is a bee based modpack. Explore worlds searching for bees. Collect bees and breed them to create new, better bees. Breeding is to much work? Then genetically modify bees to make them do anything. While on the hunt for bees you are being hunted. Monsters lurk through the night trying to kill you. Craft equipment to protect yourself throughout you adventures.\r\n\r\n<p>This modpack has a large variety of mods. All the mods can be grouped in four simple categories: Utility mods, RPG mods, tech mods, and bee mods. Bees are always going to be the main focus. There will be little things you will be distracted by like adventuring and more non-bee tech.</p>",
    "mods": [
        {
            "id": 2,
            "name": "Applied Energistics 2",
            "deck": "Applied Energistics 2 is a Minecraft Mod which contains a large amount of new content, mostly centered around the concept of using Energy,",
            "website": "http://ae-mod.info/",
            "download_link": "http://ae-mod.info/Downloads/",
            "donate_link": "http://ae-mod.info/",
            "wiki_link": "http://ae-mod.info/",
            "description": "Applied Energistics 2 is a Minecraft Mod which contains a large amount of new content, mostly centered around the concept of using Energy, and the Transformation of Energy in a unique way. most features relate, or are part of the core mechanic, the ME Network.",
            "slug": "applied-energistics-2",
            "created_at": {
                "date": "2014-11-05 20:50:21.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2014-11-05 20:51:43.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        },
        {
            "id": 9,
            "name": "Big Reactors",
            "deck": "A mod which adds multi-block power systems capable of providing large amounts of RF power to Minecraft.",
            "website": "http://www.big-reactors.com/",
            "download_link": "http://www.big-reactors.com/#/download",
            "donate_link": "http://www.big-reactors.com/",
            "wiki_link": "",
            "description": "",
            "slug": "big-reactors",
            "created_at": {
                "date": "2014-11-05 21:13:31.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2014-11-05 21:13:31.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        },
        {
            "id": 14,
            "name": "BuildCraft",
            "deck": "Extends Minecraft with pipes, auto-crafting, quarries, engines, and more.",
            "website": "http://www.mod-buildcraft.com/",
            "download_link": "http://www.mod-buildcraft.com/download/",
            "donate_link": "http://www.mod-buildcraft.com/",
            "wiki_link": "http://www.mod-buildcraft.com/wiki/",
            "description": "",
            "slug": "buildcraft",
            "created_at": {
                "date": "2014-11-05 21:33:15.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2014-11-05 21:33:15.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        },
        {
            "id": 15,
            "name": "Carpenter's Blocks",
            "deck": "Adds slopes and a custom variety of vanilla-inspired blocks to Minecraft.",
            "website": "http://www.carpentersblocks.com/",
            "download_link": "http://www.carpentersblocks.com/downloads.html",
            "donate_link": "http://www.carpentersblocks.com/",
            "wiki_link": "",
            "description": "",
            "slug": "carpenters-blocks",
            "created_at": {
                "date": "2014-11-05 21:36:15.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2014-11-05 21:36:15.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        },
        {
            "id": 18,
            "name": "CodeChickenCore",
            "deck": "A library of classes that all mods by Chicken Bones use.",
            "website": "http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956-chickenbones-mods",
            "download_link": "http://chickenbones.net/Pages/links.html",
            "donate_link": "http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1279956-chickenbones-mods",
            "wiki_link": "",
            "description": "",
            "slug": "codechickencore",
            "created_at": {
                "date": "2014-11-05 22:00:41.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2014-11-05 22:00:41.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        }
        ],
    "slug": "drone-pack",
    "created_at": {
        "date": "2015-02-02 18:44:27.000000",
        "timezone_type": 3,
        "timezone": "UTC"
    },
    "updated_at": {
        "date": "2015-02-02 18:45:34.000000",
        "timezone_type": 3,
        "timezone": "UTC"
    }
}
```