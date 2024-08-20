This file we have to define the below items to create a VM
1. VM name
2. VM Password
3. Storage account (for bootDiagnostics). 

Pre-defined values are the following 
1. Admin User Name
2. VM Size
3. Location (This inherit from the RSG location)
4. Public IP Addresses (If you dont want please remove that colume alone)
5. NIC name
6. Vnet Name and its ID
7. Subnet name and its ID
8. Data Disk Name
9. Tags set Name and the VM NAME as a Value
10. Windows O.S Specified as 2022

 ## Deploy to Azure

[![DeploytoAzure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fprnz13%2FVG-Test%2Fmain%2FCreate%2520a%2520VM%2FVM2.json)