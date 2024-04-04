---
sidebar_position: 5
---

# Hang Up Call

Allows for hanging up calls.
 #### Request type : ```post```
  #### url : ```post```/hang_up_call/

## Parameters



| Name   | Type   | In     |
|--------|--------|--------|
| apiKey*| string | query  |
|callSid*| string | query  |


``` apiKey  and callSid are required ```

`

## Responses
- 200 - Successful Response

    Media type: 'application/json'

   
    Example Value | schema 

    ```json
    {
        "string"
    }
    ```
- 422 - Validation Error

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