---
category: Accounts
path: '/v1/account/name/:name'
title: 'Retrieve account by name'
type: 'GET'

layout: nil
---

This method allows the user to get an account by name.

### Request

* **`:name`** is the name of the account.
* **The body is omitted**.

### Response

Sends back a collection of things.

```Status: 200 Deleted```
```{
    code: 200,
    message: 'Your thing (id: 736) was deleted'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).