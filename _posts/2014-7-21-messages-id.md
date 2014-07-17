---
category: Messages
path: '/v1/messages/id/:id'
title: 'Retrieve message by id'
type: 'GET'

layout: nil
---

This method allows the user to get a message by id.

### Request

* **`:id`** is the id of the message.
* **The body is omitted**.

### Response

Sends back a collection of things.

```Status: 200 Deleted```
```{
    code: 200,
    message: 'Your thing (id: 736) was deleted'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).