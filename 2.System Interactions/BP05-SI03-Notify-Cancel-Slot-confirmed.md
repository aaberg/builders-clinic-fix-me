# BP05 - SI03-Notify Cancel Slot confirmed

## Description

The system notifies the customer that the maintenance slot cancellation has been confirmed.

## Diagram

![BP05 - SI03-Notify Cancel Slot confirmed](1.SystemInteractionDiagrams/BP05-SI03-Notify-Cancel-Slot-confirmed.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Load cancelled maintenance slot | Cancelled slot reference | Cancelled slot details | Retrieves cancellation information for the message. |
| Build cancellation confirmation message | Cancelled slot details | Cancellation confirmation content | Creates the customer-facing cancellation confirmation. |
| Send cancellation confirmation email | Cancellation confirmation content | Email delivery attempt | Sends the cancellation confirmation to the customer. |
| Record notification as sent | Successful delivery result | Sent notification record | Captures successful notification delivery. |
| Record notification failure for retry | Failed delivery result | Retryable failure record | Keeps failed notifications available for retry handling. |
