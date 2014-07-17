---
category: Accounts
path: '/v1/account/type/:type'
title: 'Retrieve accounts by type'
type: 'GET'

layout: nil
---

This method allows the user to get accounts by type.

### Request

* **`:type`** is the type of the accounts.
* **The body is omitted**.

### Response

Sends back a collection of things.

```Status: 200 Deleted```
```{
    code: 200,
    message: 'Your thing (id: 736) was deleted'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).