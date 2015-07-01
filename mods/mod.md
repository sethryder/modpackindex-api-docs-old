### Description

List details for a mod, including what modpacks the mod is included in.

### Endpoint

```GET /api/v1/mod/$ID.json```

### Required Parameters

> ID = ID of the mod you are requesting.

### Sample

#### Request

```GET https://www.modpackindex.com/api/v1/mod/716.json```

#### Result

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