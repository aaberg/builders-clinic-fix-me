# BP01 - SI03-Confirm Account Registration

## Description

The system confirms the customer's registration action, validates the activation context, and activates the account when the confirmation succeeds.

## Diagram

![BP01 - SI03-Confirm Account Registration](1.SystemInteractionDiagrams/BP01-SI03-Confirm-Account-Registration.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive activation request with token and password | Activation token and password | Activation request captured | Starts account activation from the customer's confirmation link. |
| Validate registration token | Activation token | Token validation result | Confirms the token belongs to a pending registration and is still usable. |
| Validate password rules | Password | Password validation result | Ensures the password satisfies account security requirements. |
| Activate customer account | Valid token and password | Active customer account | Converts the pending registration into an active account. |
| Store credentials securely | Customer account and password | Stored credentials | Persists credentials using secure storage rules. |
| Reject activation request | Invalid token or password | Activation rejection | Stops activation when the submitted data is not valid. |
