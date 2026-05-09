# BP04 - Schedule Maintenance Slot

Source diagram: `1.WorkflowDiagrams /BP04-ScheduleMaintenanceSlot.bpmn`

## Workflow Diagram

![BP04 - Schedule Maintenance Slot](1.WorkflowDiagrams%20/BP04-ScheduleMaintenanceSlot.svg)

## Workflow Description

This workflow schedules a maintenance slot for a customer. The customer requests maintenance scheduling, the system starts the scheduling process, and a back-office representative contacts the contractor to find an available slot. The system records the slot time, notifies the customer of the available slot, and the customer either agrees or disagrees. If the customer agrees, the slot is approved and a confirmation notification is sent. If the customer disagrees, the slot is declined and the scheduling loop restarts.

## Intention

The intention is to coordinate customer, system, contractor, and back-office activity so an acceptable maintenance slot can be found, confirmed, or declined and retried.

## System Interactions

- SI01-Start Schedule Maintenance Slot
- SI02-Set Maintenance Slot Time
- SI03-Notify Customer Of Available Slot
- SI04-Approve Maintenance Slot
- SI05-Notify Maintenance Slot Confirmation
- SI06-Decline Maintenance Slot
