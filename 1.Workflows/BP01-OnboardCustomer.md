# BP01 - Onboard Customer

Source diagram: `1.WorkflowDiagrams /BP01-OnboardCustomer.bpmn`

## Workflow Diagram

![BP01 - Onboard Customer](1.WorkflowDiagrams%20/BP01-OnboardCustomer.svg)

## Workflow Description

This workflow onboards a new customer account. The customer enters an email address, requests account creation, receives a registration email, follows the link, sets a password, activates the account, and completes any required extra onboarding information before being redirected to the search page.

## Intention

The intention is to create and activate a customer account, confirm ownership through an email-based flow, collect any required onboarding details, and then move the customer into the application.

## System Interactions

- [SI01-Initiate Account Registration](../2.System%20Interactions/BP01-SI01-Initiate-Account-Registration.md)
- [SI02-Send Account Registration Notification](../2.System%20Interactions/BP01-SI02-Send-Account-Registration-Notification.md)
- [SI03-Confirm Account Registration](../2.System%20Interactions/BP01-SI03-Confirm-Account-Registration.md)
- [SI04-Add Account Information](../2.System%20Interactions/BP01-SI04-Add-Account-Information.md)
