# BP03 - Enroll Maintenance Plan

Source diagram: `1.WorkflowDiagrams /BP03-EnrollMaintenancePlan.bpmn`

## Workflow Diagram

![BP03 - Enroll Maintenance Plan](1.WorkflowDiagrams%20/BP03-EnrollMaintenancePlan.svg)

## Workflow Description

This workflow lets a customer enroll equipment in a maintenance plan. The customer starts enrollment, chooses equipment, and selects a provider. The system retrieves eligible equipment, matches providers, begins the enrollment, and records additional enrollment information. Back office validates the request and either approves or rejects the maintenance plan, after which the system sends the customer a notification.

## Intention

The intention is to guide a customer from maintenance-plan enrollment request through equipment and provider selection, support back-office validation, and complete the process with an approval or rejection notification.

## System Interactions

- [SI01-Get Equipment List](../2.System Interactions/BP03-SI01-Get-Equipment-List.md)
- [SI02-Match Providers](../2.System Interactions/BP03-SI02-Match-Providers.md)
- [SI03-Begin Enroll Maintenance Plan](../2.System Interactions/BP03-SI03-Begin-Enroll-Maintenance-Plan.md)
- [SI04-Add Information To Enroll Maintenance Plan](../2.System Interactions/BP03-SI04-Add-Information-To-Enroll-Maintenance-Plan.md)
- [SI05-Reject Maintenance Plan](../2.System Interactions/BP03-SI05-Reject-Maintenance-Plan.md)
- [SI06-Approve Maintenance Plan](../2.System Interactions/BP03-SI06-Approve-Maintenance-Plan.md)
- [SI07-Notify Approve Maintenance Plan](../2.System Interactions/BP03-SI07-Notify-Approve-Maintenance-Plan.md)
- [SI08-Notify Reject Maintenance Plan](../2.System Interactions/BP03-SI08-Notify-Reject-Maintenance-Plan.md)
