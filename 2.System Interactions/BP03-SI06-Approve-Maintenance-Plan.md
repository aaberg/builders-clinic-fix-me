# BP03 - SI06-Approve Maintenance Plan

## Description

The system records approval of the maintenance-plan enrollment request and updates the plan status for the selected equipment.

## Diagram

![BP03 - SI06-Approve Maintenance Plan](1.SystemInteractionDiagrams/BP03-SI06-Approve-Maintenance-Plan.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive approval decision | Back-office approval decision | Approval request accepted | Starts approval handling for the enrollment. |
| Set maintenance plan enrollment status to approved | Approval decision | Approved enrollment status | Updates the enrollment lifecycle state. |
| Activate maintenance plan coverage | Approved enrollment | Active maintenance plan coverage | Makes the maintenance plan effective for the equipment. |
| Trigger approval notification | Approved enrollment | Approval notification request | Starts customer notification of the approval. |
