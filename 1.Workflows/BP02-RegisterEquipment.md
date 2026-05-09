# BP02 - Register Equipment

Source diagram: `1.WorkflowDiagrams /BP02-RegisterEquipment.bpmn`

## Workflow Diagram

![BP02 - Register Equipment](1.WorkflowDiagrams%20/BP02-RegisterEquipment.svg)

## Workflow Description

This workflow lets a customer register new equipment. The customer requests registration, selects an equipment type, fills in the registration form, and submits the equipment for registration. The system retrieves the required data and form, registers the equipment, and coordinates with a back-office representative for validation before finalizing the equipment record and notifying the customer.

## Intention

The intention is to capture all information needed to create a valid equipment record, validate that registration, request additional information when needed, and finalize the equipment registration in the system.

## System Interactions

- [SI01-Retrieve Equipment Types](../2.System%20Interactions/BP02-SI01-Retrieve-Equipment-Types.md)
- [SI02-Retrieve Equipment Registration Form](../2.System%20Interactions/BP02-SI02-Retrieve-Equipment-Registration-Form.md)
- [SI03-Register Equipment](../2.System%20Interactions/BP02-SI03-Register-Equipment.md)
- [SI04-Check registration](../2.System%20Interactions/BP02-SI04-Check-registration.md)
- [SI05-Add equipment information](../2.System%20Interactions/BP02-SI05-Add-equipment-information.md)
- [SI06-Finallize Equipment](../2.System%20Interactions/BP02-SI06-Finallize-Equipment.md)
