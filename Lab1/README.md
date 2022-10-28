AZURE CLI / Powershell

Deploy a storage account/webapp :
1. Go to your template folder
2. Login   
    >> az login
3.  Create 
    >> az group create --name WebApp --location "West Europe"

Testing:
4.  >> az group deployment validate -g WebApp --template-file   azuredeploy.json --parameters "@azuredeploy.parameters.json"  
 
    >> provide string value for 'appname' : sd_web

  
