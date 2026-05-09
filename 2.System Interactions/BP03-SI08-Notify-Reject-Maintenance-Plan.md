# BP03 - SI08-Notify Reject Maintenance Plan

## Description

The system notifies the customer that the maintenance-plan enrollment request was rejected.

## Diagram

![BP03 - SI08-Notify Reject Maintenance Plan](1.SystemInteractionDiagrams/BP03-SI08-Notify-Reject-Maintenance-Plan.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive maintenance plan decision notification request | Rejection notification request | Notification request accepted | Starts customer notification for a rejected maintenance plan. |
| Load customer contact details | Rejected enrollment | Customer contact details | Retrieves the destination for the notification. |
| Build notification message with decision details | Rejection details and contact context | Rejection notification content | Creates the customer-facing rejection message. |
| Send notification email | Rejection notification content | Email delivery attempt | Sends the rejection email to the customer. |
| Record notification as sent | Successful delivery result | Sent notification record | Captures successful notification delivery. |
| Record notification failure for retry | Failed delivery result | Retryable failure record | Keeps failed notifications available for retry handling. |
