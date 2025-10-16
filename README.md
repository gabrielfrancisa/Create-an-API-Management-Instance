# Create-an-API-Management-Instance
As a Security Engineer for an organisation that needs to migrate its primary web app from its on-premises datacenter to Azure.


At the end of the project, I accomplished the following:
1. Created an Azure API Management instance.
2. Created and tested a backend API.
3. Published and monitored an API.

   
Create an Azure API Management service instance to host your APIs. 
1. First, you will create an instance of the Azure API Management service.
2. Next, you will add an API to the instance, and then you will ensure that the API responds to HTTPS requests.
3. Finally, you will publish the API, and then you will configure monitoring of the API Management instance.


## 1. Create an Azure API Management instance

Sign in to the Azure portal as Admin
Create an API Management instance named apim55553180 in the RG1lod55553180 resource group that uses Cloudslice as the organization name, Admin-55553180@cloudslice.onmicrosoft.com as the administrator email, and the Consumption pricing tier.
Expand this hint for guidance on creating an API Management instance.
Do not continue until the API Management instance deployment is complete.

You can monitor the progress of the deployment by using the Notifications option.

>>The Notifications pane
1. Verify that apim55553180 is online.
2. Do not continue until the API Management Instance status is online.

## You can create an API Management instance 
1. by using the Azure portal, 
2. the Azure command-line interface (CLI) 2.0, 
3. Azure PowerShell®, 
4. Visual Studio Code, 
5. or an Azure Resource Manager (ARM) template. When you create an instance by using the Azure portal, the default pricing tier is Developer (no SLA).


>>Azure portal
>>Azure CLI 2.0
>>Azure PowerShell®
>>Visual Studio Code
>>Azure Resource Manager (ARM) template


## 2. Create and test a backend API
1. Create an API in apim55553180 by using the OpenAPI definition and the https://petstore3.swagger.io/api/v3/openapi.json specification.
2. The default display name of your new API is Swagger Petstore - OpenAPI 3.0.
>> Review the documentation on importing an OpenAPI specification backend API in JSON format into an Azure API Management instance.
3. Configure the Swagger Petstore - OpenAPI 3.0 in apim55553180 by using an HTTPS URL scheme that has an API URL suffix of petstore.
4. Test the Swagger Petstore - OpenAPI 3.0 by using the Finds Pets by status method.
5. The Finds Pets by status request will respond with a 200 OK message and some data.

>>6lm1ais3.png



## 3. Publish an API

>>Create a product in apim55553180 by using the values in the following table. For any property that is not specified, use the default value.

Property ----------	Value
1. Display name:	Cloudslice product
2. Description	Test: Cloudslice product
3. Published:	Selected
4. Requires subscription:	Selected


## You can use a product to group multiple APIs together.
1. Add the Swagger Petstore - OpenAPI 3.0 to the Cloudslice product.
2. Monitor the Swagger Petstore - OpenAPI 3.0 to view the Capacity and Requests metrics over the last 30 minutes.
3. You can monitor metrics for an API by using the Azure portal.

The Metrics blade filtered to monitor capacity and requests

more...


## 4. Summary
Congratulations

