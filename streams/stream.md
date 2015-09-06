### Description

List details for a currently live stream.

### Endpoint

```GET /api/v1/stream/$CHANNEL_ID.json```

### Required Parameters

> ID = ID of the stream you are requesting.

### Sample

**Request**

```GET https://www.modpackindex.com/api/v1/stream/379382.json```

**Result**

```
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
        "date": "2015-09-06 05:28:11.000000",
        "timezone_type": 3,
        "timezone": "UTC"
    },
    "updated_at": {
        "date": "2015-09-06 05:28:11.000000",
        "timezone_type": 3,
        "timezone": "UTC"
    }
}
```