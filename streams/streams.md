### Description

Lists streams that are currently live and listed on the site.

### Endpoint

```GET /api/v1/streams/$MODPACK_ID.json```

### Required Parameters

> Modpack ID - Filter results to a specific modpack. You can use 'all' to get all streams.

###  Optional Parameters

> Limit - Limit the amount of results returned. 

Defaults to 100.

> Offset - Used when your results is greater then your set limit.

Defaults to 0.

### Sample

**Request**

```GET https://www.modpackindex.com/api/v1/streams/all.json?limit=2```

**Result**
```
{
    "results": [
        {
            "channel_id": 379382,
            "modpack_id": 55,
            "status": "Magic Farm 3 HARDCORE (w/ Lucky Blocks)! - #twitch #live #minecraft",
            "display_name": "Flamegoat",
            "language": "English",
            "preview_image_url": "https://static-cdn.jtvnw.net/previews-ttv/live_user_flamegoat-320x180.jpg",
            "twitch_url": "http://www.twitch.tv/flamegoat",
            "viewers": 34,
            "followers": 6298,
            "created_at": {
                "date": "2015-09-06 05:26:08.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2015-09-06 05:26:08.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        },
        {
            "channel_id": 25399871,
            "modpack_id": 7,
            "status": "A bunch of New Zealanders Playing AGRARIAN SKIES",
            "display_name": "kieranHQ",
            "language": "English",
            "preview_image_url": "https://static-cdn.jtvnw.net/previews-ttv/live_user_kieranhq-320x180.jpg",
            "twitch_url": "http://www.twitch.tv/kieranhq",
            "viewers": 0,
            "followers": 21,
            "created_at": {
                "date": "2015-09-06 05:26:08.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2015-09-06 05:26:08.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        }
    ],
    "meta": {
        "total_results": 17,
        "limit": "2",
        "offset": 0
    }
}
```