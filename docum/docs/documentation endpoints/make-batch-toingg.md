---
sidebar_position: 3
---

# Make Batch Toingg

This is used for  "Toingg" in batches

 #### Request type : ```post```
  #### url : ```post```/make_batch_toingg/

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
  "numberList": [
    {
      "clientName": "string",
      "clientNumber": "string"
    }
  ]
}
```

## Responses
-  COde: 200 - Successful Response

    Media type: 'application/json'

    
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