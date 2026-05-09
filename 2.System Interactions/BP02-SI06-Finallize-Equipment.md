# BP02 - SI06-Finallize Equipment

## Description

The system finalizes the validated equipment registration and makes the equipment record available for future customer activity.

## Diagram

![BP02 - SI06-Finallize Equipment](1.SystemInteractionDiagrams/BP02-SI06-Finallize-Equipment.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive equipment approval or denial decision | Back-office decision | Finalization request accepted | Starts final processing for the registration decision. |
| Activate equipment record | Approval decision and equipment registration | Active equipment record | Makes approved equipment available in the customer account. |
| Store final registration status | Final decision | Stored registration status | Persists the approved or denied outcome. |
| Send registration completion email | Approved equipment registration | Completion email delivery attempt | Notifies the customer that registration is complete. |
| Store denied registration status | Denial decision | Denied registration record | Records that the equipment registration was not approved. |
| Send denial notification | Denied registration record | Denial notification delivery attempt | Tells the customer the registration was denied. |
