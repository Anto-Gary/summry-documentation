---
title: Users
parent: Summry Endpoints
# grand_parent: Summry
has_children: true
# nav_order: 1
---

## /users

### Content


```js
[
    {
        "ID": number
        "username": string
        "firstName": string
        "lastName": string
        "email": string/valid email
        "summries": [
            {
                "id": int,
                "title": string, 
                "slug": string, 
                // should this endpoint show stores & queries too?
                // "stores": [],
                // "queries": []
            }
        ]        
        ~~password?:~~ // no
    }
]
```

---

**TODO:**

- [ ] edit user data (reset password, etc.)
