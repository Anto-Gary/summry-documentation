---
title: Get All Summries
parent: Summries
grand_parent: Summry Endpoints
has_children: false
# nav_order: 1
---

```js
GET /summries

[
    {
        "id": int,
        "title": string, 
        "slug": string, 
        "stores": [
            {
                "id": int,
                "url": string/valid url - how should user input?
            }
        ],
        "queries": [
            {
                "id": int,
                "merchant": string,
                "product": string,
                "price": float
            }
        ]
    }
]
```
