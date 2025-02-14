# Not used by the Action

The file *configuration.template.json* is the collection of settings required by the 2 SFTP connections that the Logic App uses. When connections get created in a logic app, a number of App Settings get created that correspond to the connection. Depending on the nature of the connection needed for the logic app flow, there will be a differing set of settings.

The configuration file has settings for 2 SFTP sites. One for the trigger and one for the destination SFTP site. These settings have had the password settings redacted. It is not safe to leave these in a repo.

The file in this folder is for reference. The action now uses the secret in APP_SETTING which is all of the connection settings including the secrets
