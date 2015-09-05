### Description

Lists modpacks that are currently on the site.

### Endpoint

```GET /api/v1/modpacks/$VERSION.json```

### Required Parameters
> Version - Filter results to include a specific version. You can use 'all' to get all versions.

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

**Request**

```GET https://www.modpackindex.com/api/v1/modpacks/1-7-10.json?limit=2```

**Result**
```
{
    "results": [
        {
            "id": 1,
            "name": "Direwolf20 1.7",
            "short_description": "Play along with Direwolf20 using the same pack he uses in his SSP YouTube series.",
            "website": "http://www.feed-the-beast.com/modpacks/direwolf20_17",
            "download_link": "http://www.feed-the-beast.com/modpacks/direwolf20_17",
            "donate_link": "http://www.feed-the-beast.com/modpacks/direwolf20_17",
            "wiki_link": "",
            "description": "",
            "slug": "direwolf20-17",
            "created_at": {
                "date": "2014-11-06 03:19:52.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2015-05-08 17:10:08.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        },
        {
            "id": 2,
            "name": "FTB Lite 3",
            "short_description": "FTB Lite is a pack built with older computers in mind. It also functions as a basic foundation pack for creators to use to expand on.",
            "website": "http://www.feed-the-beast.com/modpacks/FTBLite3",
            "download_link": "http://www.feed-the-beast.com/modpacks/FTBLite3",
            "donate_link": "http://www.feed-the-beast.com/modpacks/FTBLite3",
            "wiki_link": "",
            "description": "",
            "slug": "ftb-lite-3",
            "created_at": {
                "date": "2014-11-06 15:25:17.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            },
            "updated_at": {
                "date": "2015-01-29 18:26:46.000000",
                "timezone_type": 3,
                "timezone": "UTC"
            }
        }
    ],
    "meta": {
        "total_results": 75,
        "limit": "2",
        "offset": 0
    }
}
```