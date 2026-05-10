# BP03 - SI04-Add Information To Enroll Maintenance Plan

## Description

The system records additional enrollment details needed to complete the maintenance-plan request and prepare it for validation.

## Diagram

![BP03 - SI04-Add Information To Enroll Maintenance Plan](1.SystemInteractionDiagrams/BP03-SI04-Add-Information-To-Enroll-Maintenance-Plan.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive validated maintenance plan information | Back-office maintenance-plan information | Information update accepted | Captures validated details for the enrollment request. |
| Update enrollment request details | Validated plan information | Updated enrollment request | Stores the reviewed maintenance-plan details. |
| Store back-office validation notes | Back-office notes | Stored validation notes | Keeps the reasoning and observations from validation. |
| Evaluate whether request should be approved or rejected | Updated request and validation notes | Approval or rejection recommendation | Prepares the request for a final decision. |
