---
title: Update Summry
parent: Summries
grand_parent: Summry Endpoints
has_children: false
# nav_order: 1
---


POST (PATCH?) /summries/{id}

only new stuff gets sent

```json
{
    "stores: [
        {
            "url": string/valid url - how should user input?
        }
    ],
    "queries": [
        {
            "producer": string,
            "bottle": string,
            "price": float
        }
    ]
}
```
