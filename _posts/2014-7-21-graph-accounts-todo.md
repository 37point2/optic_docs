---
category: Graph
path: '/v1/graph/accounts/:todo'
title: 'Retrieve accounts by todo'
type: 'GET'

layout: nil
---

This method allows the user to get accounts by todo.

### Request

* **`:todo`** is the todo of the accounts.
* **The body is omitted**.

### Response

Sends back a collection of things.

```Status: 200 Deleted```
```{
    code: 200,
    message: 'Your thing (id: 736) was deleted'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).