# BP01 - Register Equipment

Source diagram: `Diagrams/BP01-RegisterEquipment.bpmn`

## Workflow Description

This workflow lets a customer register new equipment. The customer requests registration, selects an equipment type, fills in the registration form, and submits the equipment for registration. The system retrieves the required data and form, registers the equipment, and coordinates with a back-office representative for validation before finalizing the equipment record and notifying the customer.

## Intention

The intention is to capture all information needed to create a valid equipment record, validate that registration, request additional information when needed, and finalize the equipment registration in the system.

## System Interactions

- SI-Retrieve Equipment Types
- SI-Retrieve Equipment Registration Form
- SI-Register Equipment
- SI-Check registration
- SI-Add equipment information
- SI-Finallize Equipment
