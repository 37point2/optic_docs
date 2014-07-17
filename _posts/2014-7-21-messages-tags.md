---
category: Messages
path: '/v1/messages/tags/:tag'
title: 'Retrieve messages by tag'
type: 'GET'

layout: nil
---

This method allows the user to get messages by tag.

### Request

* **`:tag`** is the tag of the messages.
* **The body is omitted**.

### Response

Sends back a collection of things.

```Status: 200 Deleted```
```{
    code: 200,
    message: 'Your thing (id: 736) was deleted'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).