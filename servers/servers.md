### Description

Lists server that are currently listed on the site.

### Endpoint

```GET /api/v1/servers/$MODPACK_ID.json```

### Required Parameters

> Modpack ID - Filter results to a specific modpack. You can use 'all' to get all servers.

###  Optional Parameters

> Limit - Limit the amount of results returned. 

Defaults to 100.

> Offset - Used when your results is greater then your set limit.

Defaults to 0.

> Active - Only return servers that are currently set to active on the site (1 = True, 0 = False).

Defaults to 0.

### Sample

**Request**

```GET https://www.modpackindex.com/api/v1/servers/all.json?limit=2```

**Result**
```
{
    "results": [
        {
            "id": 3,
            "modpack_id": 52,
            "name": "OTEGamers Modded MC Network (TPPI)",
            "short_description": "The OTE TPPI2 Server!",
            "server_address": "tppi.otegamers.com:25565",
            "country": "US",
            "permissions": 1,
            "website": null,
            "application_url": "Get Whitelisted:\r\nWe are a whitelist community. Our whitelist grants you access to all current and future servers. Staff are very quick to respond to whitelists (Within 10 minutes most of the time).\r\n\r\nIRC Channel:\r\nOur IRC is linked into all of our community Minecraft servers. If you want to chat to us or get whitelisted quickly. \r\n\r\nhttps://kiwiirc.com/client/irc.esper.net/?channel_list_style=tabs#OTEGamers\r\n\r\nServer Rules:\r\nOur rules are located over on our forums. Make sure to read them in full \r\n\r\nhttp://www.otegamers.com/link-forums/community-rules-guidelines.224/",
            "description": "otegamers-modded-mc-network-tppi",
            "server_address_hide": null,
            "player_list_hide": null,
            "slug": "otegamers-modded-mc-network-tppi",
            "last_world_reset": null,
            "next_world_reset": null,
            "created_at": {
                "date": "2015-07-29 00:45:11.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2015-09-05 23:49:11.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        },
        {
            "id": 4,
            "modpack_id": 45,
            "name": "OTEGamers Modded MC Network (Infinity)",
            "short_description": "The OTE Infinity Server!",
            "server_address": "infinity.otegamers.com:25565",
            "country": "US",
            "permissions": 1,
            "website": null,
            "application_url": "Get Whitelisted:\r\nWe are a whitelist community. Our whitelist grants you access to all current and future servers. Staff are very quick to respond to whitelists (Within 10 minutes most of the time).\r\n\r\nIRC Channel:\r\nOur IRC is linked into all of our community Minecraft servers. If you want to chat to us or get whitelisted quickly. \r\n\r\nhttps://kiwiirc.com/client/irc.esper.net/?channel_list_style=tabs#OTEGamers\r\n\r\nServer Rules:\r\nOur rules are located over on our forums. Make sure to read them in full \r\n\r\nhttp://www.otegamers.com/link-forums/community-rules-guidelines.224/",
            "description": "otegamers-modded-mc-network-infinity",
            "server_address_hide": null,
            "player_list_hide": null,
            "slug": "otegamers-modded-mc-network-infinity",
            "last_world_reset": null,
            "next_world_reset": null,
            "created_at": {
                "date": "2015-07-29 00:51:49.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2015-09-05 23:49:11.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        }
    ],
    "meta": {
        "total_results": 10,
        "limit": "2",
        "offset": 0
    }
}
```