# BP04 - SI02-Set Maintenance Slot Time

## Description

The system records the proposed maintenance-slot time after availability has been coordinated with the contractor.

## Diagram

![BP04 - SI02-Set Maintenance Slot Time](1.SystemInteractionDiagrams/BP04-SI02-Set-Maintenance-Slot-Time.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive proposed slot from back office | Proposed maintenance slot | Slot proposal accepted | Captures the time proposed after contractor coordination. |
| Validate slot date and time | Proposed slot | Slot validation result | Ensures the proposed slot is usable. |
| Store proposed maintenance slot | Valid proposed slot | Stored proposed slot | Persists the slot for customer review. |
| Mark slot as allocated pending customer response | Stored proposed slot | Pending customer response status | Reserves the slot while waiting for customer agreement. |
