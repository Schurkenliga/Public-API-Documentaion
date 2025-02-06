---
sidebar_position: 3
---

# Rate Limit
Die API hat ein "Rate Limit" (Durchsatzratenbegrenzung) von:
**50 Anfragen** in **5 Minutern**.
Anfragen die über dieses Limit hinaus gehen bekommen folgendes Zurück.
```http
HTTP status code 429
```

:::info
Der HTTP status code ``429`` ist in Sektion 4 definiert von **IETF’s RFC 6585**.
Lese mehr zu den HTTP status codes bei [Developer Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status).


