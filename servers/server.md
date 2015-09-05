### Description

List details for a server, including players and mods (if they are not set to private and are properly returned by the server).

### Endpoint

```GET /api/v1/server/$ID.json```

### Required Parameters

> ID = ID of the server you are requesting.

### Sample

**Request**

```GET https://www.modpackindex.com/api/v1/server/4.json```

**Result**

```
{
    "id": 1,
    "modpack_id": 18,
    "name": "MPI Test Server 1.6.4",
    "short_description": "Testing server #1.",
    "server_address": "Hidden",
    "country": "CA",
    "permissions": 1,
    "website": null,
    "application_url": "This server is for testing!",
    "description": "mpi-test-server-164",
    "players": [],
    "mods": [
        {
            "name": "mcp",
            "version": "9.05"
        },
        {
            "name": "FML",
            "version": "7.10.99.99"
        },
        {
            "name": "Forge",
            "version": "10.13.3.1408"
        },
        {
            "name": "appliedenergistics2-core",
            "version": "rv2-stable-3"
        },
        {
            "name": "Aroma1997Core",
            "version": "1.0.2.13"
        },
        {
            "name": "CodeChickenCore",
            "version": "1.0.6.43"
        },
        {
            "name": "InfiniBows",
            "version": "1.3.0 build 20"
        },
        {
            "name": "MobiusCore",
            "version": "1.2.5"
        },
        {
            "name": "NotEnoughItems",
            "version": "1.0.4.107"
        },
        {
            "name": "ThaumicTinkerer-preloader",
            "version": "0.1"
        }
    ],
    "server_address_hide": 1,
    "player_list_hide": 1,
    "slug": "mpi-test-server-164",
    "last_world_reset": "0000-00-00",
    "next_world_reset": "0000-00-00",
    "created_at": {
        "date": "2015-07-28 17:32:14.000000",
        "timezone_type": 3,
        "timezone": "UTC"
    },
    "updated_at": {
        "date": "2015-08-03 01:36:21.000000",
        "timezone_type": 3,
        "timezone": "UTC"
    }
}
```