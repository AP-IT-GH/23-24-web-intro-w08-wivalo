# 💻 08. API's uitlezen > oefening 06

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een authentication token.

### Postman opstarten

 - Start Postman.

### authentificatie met token

 - [API: Auth0 Management API](https://auth0.com/docs/api/management/v2)
 - endpoint: /users

---

1. Maak een nieuw verzoek naar de API.
2. Gebruik de endpoint /users.
3. Voeg een Authorization header toe met een Bearer Token.
4. Voer het verzoek uit en bekijk de lijst met gebruikers.

Bearer token zie token.md'
GET https://dev-og5a34zif8jk04vn.us.auth0.com/api/v2/users




  [
    {
        "created_at": "2024-04-21T13:23:24.031Z",
        "email": "wietse.vanlombergen@student.ap.be",
        "email_verified": false,
        "identities": [
            {
                "connection": "Username-Password-Authentication",
                "user_id": "6625134cea3bf6e71f4717cf",
                "provider": "auth0",
                "isSocial": false
            }
        ],
        "name": "wietse.vanlombergen@student.ap.be",
        "nickname": "wietse.vanlombergen",
        "picture": "https://s.gravatar.com/avatar/7796fd3d831e4b026a85e53dde7aae6d?s=480&r=pg&d=https%3A%2F%2Fcdn.auth0.com%2Favatars%2Fwi.png",
        "updated_at": "2024-04-21T13:23:24.031Z",
        "user_id": "auth0|6625134cea3bf6e71f4717cf"
    }
]
