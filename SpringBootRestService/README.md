### How to publish the contract to pactflow
Add the provider plugin to your consumer project
```
au.com.dius.pact.provider
```
Go to run
Configurations
Maven Build
In goals put: pact:publish
Go to run as and put the base directory and run with your new maven build configuration
```
${workspace_loc:/SpringBootRestService}
```