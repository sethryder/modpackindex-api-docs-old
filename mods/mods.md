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

> Limit - Limit the amount of results returned. 

Defaults to 100.

> Offset - Used when your results is greater then your set limit.

Defaults to 0.

### Sample

#### Request

```GET https://www.modpackindex.com/api/v1/mods/1-7-10.json?limit=2```

#### Result

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