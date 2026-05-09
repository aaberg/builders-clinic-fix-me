# BP03 - SI05-Reject Maintenance Plan

## Description

The system records the rejection of a maintenance-plan enrollment request and prepares the rejection outcome for customer notification.

## Diagram

![BP03 - SI05-Reject Maintenance Plan](1.SystemInteractionDiagrams/BP03-SI05-Reject-Maintenance-Plan.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive rejection decision | Back-office rejection decision | Rejection request accepted | Starts rejection handling for the enrollment. |
| Set maintenance plan enrollment status to rejected | Rejection decision | Rejected enrollment status | Updates the enrollment lifecycle state. |
| Store rejection reason | Rejection reason | Stored rejection reason | Records why the maintenance plan was rejected. |
| Trigger rejection notification | Rejected enrollment | Rejection notification request | Starts customer notification of the rejection. |
