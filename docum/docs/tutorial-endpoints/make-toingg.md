---
sidebar_position: 1
---


# Make Toingg

This endpoint enables users to initiate a process to "Toingg".


 #### Request type : ```post```
  #### url : ```post```/make_toingg/
## Parameters



| Name  | Type   | In     |
|-------|--------|--------|
| apiKey| string | query  |

``` apiKey is required ```

## Request body

``` request body is required ```

**Media type**: `application/json`

#### Example Value | schema

```json
{
  "campaign": "string",
  "name": "string",
  "phoneNumber": "string"
}
```

## Responses
-  Code:200 - Successful Response

    Media type: 'application/json'

    Controls Accept header.
    Example Value | schema 

    ```json
    {
        "string"
    }
    ```
-  Code: 422 - Validation Error

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