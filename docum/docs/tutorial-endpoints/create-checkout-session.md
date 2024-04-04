---
sidebar_position: 6
---
# Create Checkout Session

Initiate a checkout session for processing payments with Stripe.


 #### Request type : ```post```
  #### url : ```post```/create_checkout_session/

## Parameters


``` No Parameter ```

## Request body
``` Request Body is required ```
**Media type**: `application/json`

#### Example Value | schema

```json
{
  "apikey": "string"
}
```

## Responses
- 200 - Successful Response

    Media type: 'application/json'

    Controls Accept header.
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