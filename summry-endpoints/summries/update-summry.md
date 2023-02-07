---
title: Update Summry By ID
parent: Summries
grand_parent: Summry Endpoints
has_children: false
# nav_order: 1
---

### Update Summry By ID

```js
PUT /summries/{id}

{
    "stores": [
        {
            "url": string/valid url - how should user input?
        }
    ],
    "queries": [
        {
            "merchant": string,
            "product": string,
            "price": float
        }
    ]
}
```
