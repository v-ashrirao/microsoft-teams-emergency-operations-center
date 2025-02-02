# Known Limitations


# FAQs

## 1. Azure deployment failed with conflict error, what do I need to do?
Deployment can fail if the base resource name provided is not available and you could see conflict error. Choose a different "Base Resource Name". You can check if your desired name is available by going to the page to [create a new web app](https://portal.azure.com/#create/Microsoft.WebSite) in the Azure Portal. Enter your desired name in the "App name" field. An error message will appear if the name you have chosen is taken or invalid.

## 2. Provisioning failed with error, what do I need to do?
Provisioning can fail due to some network issue.

![ProvisioningError](Images/ProvisioningError.jpg)

If it failed and TEOC site collection is created in your tenant then delete the site collection from Active sites as well as Deleted sites. Run the provisioning script again.