# BP03 - SI02-Match Providers

## Description

The system matches available providers to the selected equipment and maintenance-plan context so the customer can choose a suitable provider.

## Diagram

![BP03 - SI02-Match Providers](1.SystemInteractionDiagrams/BP03-SI02-Match-Providers.svg)

## Operations

| Operation | Input | Output | Notes |
| --- | --- | --- | --- |
| Receive selected equipment | Selected equipment | Provider matching request accepted | Starts provider matching for the selected equipment. |
| Read equipment type and service needs | Selected equipment | Matching criteria | Extracts the criteria needed to find providers. |
| Find providers matching equipment and location | Matching criteria | Provider search result | Locates providers that can service the equipment. |
| Return provider options | Matching providers | Provider option list | Presents eligible providers to the customer. |
| Return no matching providers message | Empty provider search result | No providers message | Reports that no providers are currently available. |
