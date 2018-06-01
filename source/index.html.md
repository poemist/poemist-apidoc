---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell

toc_footers:


includes:
  - errors

search: true
---

# Introduction

Welcome to the Poemist API! You can use our API to access Poemist API endpoints, which can get information on various poets and poems in our database.



# Misc. Services

## Get Random Poems


```shell
curl "https://www.poemist.com/api/v1/randompoems"
```

> The above command returns JSON structured like this:

```json
[
  {
    "title": "Go Back To The Tainted Lap, Leah",
    "content": "Go back to the tainted lap, Leah,\nWhence you came,\nBecau... rest of the poem will be here",
    "url": "https://www.poemist.com/osip-emilevic-mandelstam/go-back-to-the-tainted-lap-leah",
    "poet": {
      "name": "Osip Emilevic Mandelstam",
      "url": "https://www.poemist.com/osip-emilevic-mandelstam"
    }
  },
  {
    "title": "Since Then",
    "content": "I found myself among the trees\nWhat time the reapers ceased to reap;\nAnd in the ... rest of the poem will be here",
    "url": "https://www.poemist.com/madison-julius-cawein/since-then",
    "poet": {
      "name": "Madison Julius Cawein",
      "url": "https://www.poemist.com/madison-julius-cawein"
    }
  },
]
```

This endpoint retrieves random poems.

### HTTP Request

`GET https://www.poemist.com/api/v1/randompoems`

### Query Parameters

There is no parameters for this service.

