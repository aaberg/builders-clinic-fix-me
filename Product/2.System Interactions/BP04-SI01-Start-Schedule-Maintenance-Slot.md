# BP04 - SI01-Start Schedule Maintenance Slot

## Description

The system starts the maintenance-slot scheduling process after the customer requests a slot for maintenance work.

## Diagram

![BP04 - SI01-Start Schedule Maintenance Slot](1.SystemInteractionDiagrams/BP04-SI01-Start-Schedule-Maintenance-Slot.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive maintenance scheduling request | Scheduling request | Request accepted | Starts scheduling for maintenance work. |
| Validate active maintenance plan | Customer and equipment context | Maintenance-plan validation result | Confirms the customer is eligible to schedule maintenance. |
| Create scheduling request | Valid scheduling context | Scheduling request record | Stores the request for coordination. |
| Send request to back office for contractor coordination | Scheduling request record | Back-office coordination task | Hands off scheduling to back office. |
