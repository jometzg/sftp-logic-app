# Secure File Transfer Logic App
This is a demo on how to do infra as code and automated deployment of an SFTP logic app.

This repo concentrates initially on how to handle the workflows, their connections and the secrets needed for these connections.

A later version will build the whole Logic App using a bicep file.

## Steps
1. Connect to to the CLI using the service principal
2. Create app connection related app settings from the values stored in APP_SETTINGS
3. Take the workflow definition and hosts and connections and zip these ready for deployment
4. Deploy the zip file to the logic app using the zip created from the previous step

## Alternative Approaches
1. use the az cli to deploy app settings one by one, grabbing secrets only where needed
2. potentially deploy all as a file from the repo as opposed to using a secret for this
