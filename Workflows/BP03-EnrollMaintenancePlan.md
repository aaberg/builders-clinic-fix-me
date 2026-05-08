# BP03 - Enroll Maintenance Plan

Source diagram: `Diagrams/BP03-EnrollMaintenancePlan.bpmn`

## Workflow Description

This workflow lets a customer enroll equipment in a maintenance plan. The customer starts enrollment, chooses equipment, and selects a provider. The system retrieves eligible equipment, matches providers, begins the enrollment, and records additional enrollment information. Back office validates the request and either approves or rejects the maintenance plan, after which the system sends the customer a notification.

## Intention

The intention is to guide a customer from maintenance-plan enrollment request through equipment and provider selection, support back-office validation, and complete the process with an approval or rejection notification.

## System Interactions

- SI-Get Equipment List
- SI-Match Providers
- SI-Begin Enroll Maintenance Plan
- SI-Add Information To Enroll Maintenance Plan
- SI-Reject Maintenance Plan
- SI-Approve Maintenance Plan
- SI-Notify Reject Maintenance Plan
- SI-Notify Reject Maintenance Plan
