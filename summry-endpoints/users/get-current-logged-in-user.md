---
title: Get Current Logged In User
parent: Users
grand_parent: Summry Endpoints
has_children: false
nav_order: 3
---

```js
GET /users/me

[
    {
        "id": number
        "username": string
        "firstName": string
        "lastName": string
        "email": string/valid email
        "summries": [id1: int, id2: int, ...] or empty if none
        ~~password?:~~
    }
]
```
