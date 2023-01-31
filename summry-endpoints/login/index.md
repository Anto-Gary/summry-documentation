---
title: Login
parent: Summry Endpoints
# grand_parent: Summry
has_children: false
nav_order: 1
---

## /login

```js
POST {{base_url}}/api/Login
Content-Type: application/json

  {
    "email": string,
    "password": string
  }
```