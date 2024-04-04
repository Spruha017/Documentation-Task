---
sidebar_position: 4
---

# Send SMS

This endpoint  is used to send SMS messages.


 #### Request type : ```post```
  #### url : ```post```/send_sms/

## Parameters



| Name  | Type   | In     |
|-------|--------|--------|
| apiKey| string | query  |

``` apiKey is required ```

## Request body

``` Request body is required ```

**Media type**: `application/json`

#### Example Value | schema

```json
{
  "name": "string",
  "phoneNumber": "string",
  "message": "string"
}
```

## Responses
- Code: 200 - Successful Response

    Media type: 'application/json'

    Controls Accept header.
    Example Value | schema 

    ```json
    {
        "string"
    }
    ```
- Code: 422 - Validation Error

    Media type: 'application/json'

    Example Value | schema 
    ```json
       {
            "detail": [
                {
                "loc": [
                    "string",
                    0
                ],
                "msg": "string",
                "type": "string"
                }
            ]
        }

     ```