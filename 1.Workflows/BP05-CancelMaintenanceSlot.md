# BP05 - Cancel Maintenance Slot

Source diagram: `1.WorkflowDiagrams /BP05-CancelMaintenanceSlot.bpmn`

## Workflow Diagram

![BP05 - Cancel Maintenance Slot](1.WorkflowDiagrams%20/BP05-CancelMaintenanceSlot.svg)

## Workflow Description

This workflow cancels an existing maintenance slot. The customer requests the cancellation, the system starts the cancellation process, and a back-office representative manually cancels the slot by contacting the provider. The system then confirms the cancellation and notifies the customer that the slot has been cancelled.

## Intention

The intention is to ensure a maintenance slot cancellation is coordinated with the provider, confirmed in the system, and communicated back to the customer.

## System Interactions

- SI01-Start Cancel Maintenance Slot
- SI02-Confirm Cancel Maintenance Slot
- SI03-Notify Cancel Slot confirmed
