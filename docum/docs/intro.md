---
sidebar_position: 1
---
# Introduction

This documentation outlines the APIs available for integrating with our system to facilitate various functionalities such as making calls, sending SMS messages, handling webhooks, and processing payments using Stripe.

## Available Endpoints
- POST /make_toingg/: This endpoint enables users to initiate a process to "Toingg".
- POST /make_toingg_details/: Use this endpoint to provide additional details for the "Toingg" process.
- POST /make_batch_toingg/: Allows for making "Toingg" in batches.
- POST /send_sms/: Use this endpoint to send SMS messages.
- POST /hang_up_call/: Allows for hanging up calls.
- POST /create-checkout-session: Initiate a checkout session for processing payments with Stripe.
- POST /webhook: Receive and handle webhook events from Stripe.
## Schemas
- APIKey : Contains the structure for an API key, which is required for accessing protected endpoints.
- HTTPValidationError: Represents the error response format for validation errors.
- ValidationError: Represents detailed validation error information.
- makeBatchCallData: Structure for data required to initiate batch call processes.
- makeCallData: Structure for data required to initiate call processes.
- makeCallDetailsData: Structure for providing additional details for call processes.
- numberData: Data structure for phone numbers.
- smsData: Structure for sending SMS messages.

This documentation provides detailed information on each API endpoint, including request and response formats, along with the schemas used for data validation and processing.

