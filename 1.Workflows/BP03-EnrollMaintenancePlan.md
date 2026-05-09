# BP03 - Enroll Maintenance Plan

Source diagram: `1.WorkflowDiagrams /BP03-EnrollMaintenancePlan.bpmn`

## Workflow Diagram

![BP03 - Enroll Maintenance Plan](1.WorkflowDiagrams%20/BP03-EnrollMaintenancePlan.svg)

## Workflow Description

This workflow lets a customer enroll equipment in a maintenance plan. The customer starts enrollment, chooses equipment, and selects a provider. The system retrieves eligible equipment, matches providers, begins the enrollment, and records additional enrollment information. Back office validates the request and either approves or rejects the maintenance plan, after which the system sends the customer a notification.

## Intention

The intention is to guide a customer from maintenance-plan enrollment request through equipment and provider selection, support back-office validation, and complete the process with an approval or rejection notification.

## System Interactions

- SI01-Get Equipment List
- SI02-Match Providers
- SI03-Begin Enroll Maintenance Plan
- SI04-Add Information To Enroll Maintenance Plan
- SI05-Reject Maintenance Plan
- SI06-Approve Maintenance Plan
- SI07-Notify Approve Maintenance Plan
- SI08-Notify Reject Maintenance Plan
