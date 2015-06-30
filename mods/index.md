# Mod Endpoints

## Mods

### Description

Lists mods that are currently on the site.

### Endpoint

```GET /api/v1/mods/$VERSION.json```

### Required Parameters
>Version - Filter results to include a specific version. You can use 'all' to get all versions.

Current supported versions include:
	* all
	* 1-6-4 (1.6.4)
	* 1-7-10 (1.7.10)

###  Optional Parameters

>Limit - Limit the amount of results returned. 

Defaults to 100.

>Offset - Used when your results is greater then your set limit.

Defaults to 0.

### Sample Result

```
{
    "results": [
        {
            "id": 1,
            "name": "AOBD 2",
            "deck": "Automatically detects every single ore from every single mod you have installed and creates the necessary dusts and etc in order for that metal to be processed on several mod's machines!",
            "website": "http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1293528-aobd-2-process-all-the-ores",
            "download_link": "",
            "donate_link": "http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1293528-aobd-2-process-all-the-ores",
            "wiki_link": "",
            "description": "AOBD has grown further than being a simple TIC add-on to allow Ardite and Cobalt processing. It now automatically detects every single ore from every single mod you have installed and creates the necessary dusts and etc in order for that metal to be processed on several mod's machines!",
            "slug": "aobd-2",
            "created_at": {
                "date": "2014-11-05 20:47:54.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2015-01-08 21:04:05.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        },
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
        }
    ],
    "meta": {
        "total_results": 794,
        "limit": "2",
        "offset": 0
    }
}
```

## Mod

### Description

List details for a mod, including what Modpacks the mod is included in.

### Endpoint

```GET /api/v1/mod/$ID.json```

### Required Parameters

 >ID = ID of the Mod you are requesting.

### Sample Result

```
{
    "id": 716,
    "name": "Cart Livery",
    "deck": "Allows you to paint your carts in all 16 glorious sheep colors, and apply colored stickers to them.",
    "website": "http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2091897-cartlivery",
    "download_link": "http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2091897-cartlivery",
    "donate_link": "http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2091897-cartlivery",
    "wiki_link": "",
    "descriptions": null,
    "modpacks": [
        {
            "id": 64,
            "name": "A Simple Life",
            "deck": "A lite pack that aims at creating living communities and lands of adventure.",
            "website": "http://www.curse.com/modpacks/minecraft/229739-a-simple-life",
            "download_link": "http://www.curse.com/modpacks/minecraft/229739-a-simple-life",
            "donate_link": "http://www.curse.com/modpacks/minecraft/229739-a-simple-life",
            "wiki_link": "",
            "descriptions": null,
            "slug": "a-simple-life",
            "created_at": {
                "date": "2015-05-16 15:52:22.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2015-06-22 02:22:27.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        }
    ],
    "slug": "cart-livery",
    "created_at": {
        "date": "2015-05-16 15:39:03.000000",
        "timezone_type": 3,
        "timezone": "UTC"
    },
    "updated_at": {
        "date": "2015-05-16 15:39:03.000000",
        "timezone_type": 3,
        "timezone": "UTC"
    }
}
```