---
title: Get Summries
parent: Summries
grand_parent: Summry Endpoints
has_children: false
# nav_order: 1
---

GET /summries

```json
[
    {
        "id": int,
        "title": string, 
        "slug": string, 
        "stores: [
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
