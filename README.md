---
services: media-services
platforms: dotnet
author: Juliako
---

# Using Azure Media Services to Dynamically encrypt your assets with AES-128 

The sample shows how to use Azure Media Services to dynamically encrypt your content with AES 128-bit clear encryption keys. 

## How To Run This Sample

To run this sample you will need:

- Visual Studio 2013 or 2015
- An Internet connection
- An Azure subscription

### Step 1:  Clone or download this repository

### Step 2: Update the app.config file

Update the appSettings section of the app.config file with appropriate values. For more information, see [this](https://docs.microsoft.com/azure/media-services/media-services-use-aad-auth-to-access-ams-api) topic.

	<appSettings>
		<add key="AMSAADTenantDomain" value="AADTenantDomain" />
		<add key="AMSRESTAPIEndpoint" value="RESTAPIEndpoint" />

		<add key="Issuer" value="http://testacs.com" />
		<add key="Audience" value="urn:test" />
	</appSettings>

### Step 3: Start a streaming endpoint

Make sure to start the streaming endpoint. For more information, see: [streaming endpoints](https://docs.microsoft.com/azure/media-services/media-services-portal-manage-streaming-endpoints).

### Step 4:  Run the sample

Clean the solution, rebuild the solution, and run it. 

## About the code

For detailed information about the sample, see [Using AES-128 Dynamic Encryption and Key Delivery Service](https://azure.microsoft.com/documentation/articles/media-services-protect-with-aes128/).

## More information

You can view AMS learning paths here:

- [AMS Live Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-live/)
- [AMS on Demand Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-on-demand/)
