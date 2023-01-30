---
title: Summries
parent: Summry Endpoints
has_children: true
# nav_order: 2
---


# Endpoints

## Summries

Summries Fields:

```json
[
    {
        "id": int,
        "title": string, 
        "slug": string,
        "createdOn": datetime,
        "updatedOn": datetime,
        "stores": [
            {
                "id": int,
                "url": string/valid url - how should user input?
            }
        ],
        "queries": [
            {
                "id": int,
                "producer": string,
                "bottle": string,
                "price": float
            }
        ]
    }
]
```


