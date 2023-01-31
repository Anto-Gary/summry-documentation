---
title: Get User By ID
parent: Users
grand_parent: Summry Endpoints
has_children: false
nav_order: 1
---

```js
GET /users/{id}

[
    {
        "ID": number
        "username": string
        "firstName": string
        "lastName": string
        "email": string/valid email
        "summries": [id1: int, id2: int, ...] or empty if none
        ~~password?:~~
    }
]
```
