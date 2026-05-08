# BP01 - Register Equipment

Source diagram: `1.WorkflowDiagrams /BP01-RegisterEquipment.bpmn`

## Workflow Description

This workflow lets a customer register new equipment. The customer requests registration, selects an equipment type, fills in the registration form, and submits the equipment for registration. The system retrieves the required data and form, registers the equipment, and coordinates with a back-office representative for validation before finalizing the equipment record and notifying the customer.

## Intention

The intention is to capture all information needed to create a valid equipment record, validate that registration, request additional information when needed, and finalize the equipment registration in the system.

## System Interactions

- SI01-Retrieve Equipment Types
- SI02-Retrieve Equipment Registration Form
- SI03-Register Equipment
- SI04-Check registration
- SI05-Add equipment information
- SI06-Finallize Equipment
