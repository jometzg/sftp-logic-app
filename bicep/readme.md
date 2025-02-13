# Infrastructure as Code
This folder contains the bicep file to deploy the logic app itself.

This has several components:
1. the server farm that is the compute for the logic app (may be shared with other logic apps)
2. the logic app itself
3. A storage account for state management of the logic app
4. An Application Insights instance for diagnostics

All of the names should be driven via a variables file. Where variables are needed as output from the deployment, these will be declared as output variables. The values of these output variables can then be used in later steps of a GitHub Action to deploy the code and configuration correctly.
