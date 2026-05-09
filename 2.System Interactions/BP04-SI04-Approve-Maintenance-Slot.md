# BP04 - SI04-Approve Maintenance Slot

## Description

The system records the customer's approval of the proposed maintenance slot and marks the slot as accepted.

## Diagram

![BP04 - SI04-Approve Maintenance Slot](1.SystemInteractionDiagrams/BP04-SI04-Approve-Maintenance-Slot.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive customer agreement | Customer slot agreement | Agreement captured | Starts approval when the customer accepts the proposed slot. |
| Confirm proposed maintenance slot | Agreement and proposed slot | Confirmed slot | Locks in the accepted maintenance slot. |
| Update slot status to approved | Confirmed slot | Approved slot status | Persists the final customer-approved state. |
| Trigger confirmation notification | Approved slot | Confirmation notification request | Starts customer notification of the confirmed slot. |
