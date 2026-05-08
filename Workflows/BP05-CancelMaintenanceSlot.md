# BP05 - Cancel Maintenance Slot

Source diagram: `Diagrams/BP05-CancelMaintenanceSlot.bpmn`

## Workflow Description

This workflow cancels an existing maintenance slot. The customer requests the cancellation, the system starts the cancellation process, and a back-office representative manually cancels the slot by contacting the provider. The system then confirms the cancellation and notifies the customer that the slot has been cancelled.

## Intention

The intention is to ensure a maintenance slot cancellation is coordinated with the provider, confirmed in the system, and communicated back to the customer.

## System Interactions

- SI-Start Cancel Maintenance Slot
- SI-Confirm Cancel Maintenance Slot
- SI-Notify Cancel Slot confirmed
