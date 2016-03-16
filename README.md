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

### Step 1:  Clone or download this repository.

### Step 2: Update the app.config file

Update the appSettings section of the app.config file with values of your Azure Media Services account.

		  <appSettings>
		    <add key="MediaServicesAccountName" value="MediaServicesAccountName" />
		    <add key="MediaServicesAccountKey" value="MediaServicesAccountKey" />
		    <add key="Issuer" value="http://testacs.com" />
		    <add key="Audience" value="urn:test" />
		  </appSettings>
		  
### Step 3: Get at least one streaming unit

Get at least one streaming unit for the streaming endpoint from which you plan to delivery your content. For more information, see: [configure streaming endpoints](http://azure.microsoft.com/documentation/articles/media-services-dotnet-get-started/#configure-streaming-endpoint-using-the-portal)

### Step 4:  Run the sample

Clean the solution, rebuild the solution, and run it. 


## About the code

For detailed information about the sample, see [Using AES-128 Dynamic Encryption and Key Delivery Service](https://azure.microsoft.com/documentation/articles/media-services-protect-with-aes128/).

## More information

You can view AMS learning paths here:

- [AMS Live Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-live/)
- [AMS on Demand Streaming Workflow](http://azure.microsoft.com/documentation/learning-paths/media-services-streaming-on-demand/)
