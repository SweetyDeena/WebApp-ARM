"Publish Azure Web Apps and App service plan using an ARM Template"

Using these templates, Azure Web Apps and App service plan can be deployed.

Running the deployment:

->To deploy a template, sign in to either the Azure CLI or Azure PowerShell

     az login
     
->Create a resource group

     az group create --name resourceGroupName --location "<location>"
     
->Deploy template

     az deployment group create --name DeployLocalTemplate --resource-group $resourceGroupName --template-file <PATH-TO-appservice.JSON> --parameters <PATH-TO-appservice.PARAMETERS.JSON> 
  
   

  
 
