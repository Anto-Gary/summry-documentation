---
title: Update Summry By ID
parent: Summries
grand_parent: Summry Endpoints
has_children: false
# nav_order: 1
---

### Update Summry By ID

```js
PATCH /summries/{id}

{
    "stores": [
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
