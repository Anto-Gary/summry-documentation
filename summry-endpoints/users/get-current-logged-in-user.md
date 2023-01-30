---
title: Get Current Logged In User
parent: Users
grand_parent: Summry Endpoints
has_children: false
nav_order: 3
---

GET current logged in user

---

/users/me

```json
[{
"id": number
"username": string
"firstName": string
"lastName": string
"email": string/valid email
"summries": [id1: int, id2: int, ...] or empty if none
~~password?:~~
}]
```
