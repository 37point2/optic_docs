---
category: Graph
path: '/v1/graph/tags/:todo'
title: 'Retrieve tags by todo'
type: 'GET'

layout: nil
---

This method allows the user to get tags by todo.

### Request

* **`:todo`** is the todo of the tags.
* **The body is omitted**.

### Response

Sends back a collection of things.

```Status: 200 Deleted```
```{
    code: 200,
    message: 'Your thing (id: 736) was deleted'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).