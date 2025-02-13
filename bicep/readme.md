# Infrastructure as Code
This folder contains the bicep file to deploy the logic app itself.

This has several components:
1. the server farm that is the compute for the logic app (may be shared with other logic apps)
2. the logic app itself
3. A storage account for state management of the logic app
4. An Application Insights instance for diagnostics
