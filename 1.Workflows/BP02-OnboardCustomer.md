# BP02 - Onboard Customer

Source diagram: `1.WorkflowDiagrams /BP02-OnboardCustomer.bpmn`

## Workflow Diagram

![BP02 - Onboard Customer](1.WorkflowDiagrams%20/BP02-OnboardCustomer.svg)

## Workflow Description

This workflow onboards a new customer account. The customer enters an email address, requests account creation, receives a registration email, follows the link, sets a password, activates the account, and completes any required extra onboarding information before being redirected to the search page.

## Intention

The intention is to create and activate a customer account, confirm ownership through an email-based flow, collect any required onboarding details, and then move the customer into the application.

## System Interactions

- SI01-Initiate Account Registration
- SI02-Send Account Registration Notification
- SI03-Confirm Account Registration
- SI04-Add Account Information
