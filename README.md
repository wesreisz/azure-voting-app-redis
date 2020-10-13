# Azure Voting App

This sample creates a PCF application that leverages a service created by redis. To use:

- Create a service after redis tile is installed: ` cf create-service p-redis shared-vm voting-app-redis`
- Push the app `cf push azure-vote`
- Bind the service to the app `cf bind-service voting-app voting-app-redis`