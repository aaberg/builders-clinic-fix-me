# BP02 - Onboard Customer

Source diagram: `Diagrams/BP02-OnboardCustomer.bpmn`

## Workflow Description

This workflow onboards a new customer account. The customer enters an email address, requests account creation, receives a registration email, follows the link, sets a password, activates the account, and completes any required extra onboarding information before being redirected to the search page.

## Intention

The intention is to create and activate a customer account, confirm ownership through an email-based flow, collect any required onboarding details, and then move the customer into the application.

## System Interactions

- SI-Initiate Account Registration
- SI-Confirm Account Registration
- SI-Add Account Information
- SI-Send Account Registration Notification
