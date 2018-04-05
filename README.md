# Managed-service-identities

Managed Service Identity (MSI) is a public GA feature of Azure Active Directory

A common challenge when building cloud applications is how to manage the credentials that need to be in your code for authenticating to cloud services. Keeping these credentials secure is an important task. Ideally, they never appear on developer workstations or get checked into source control. Azure Key Vault provides a way to securely store credentials and other keys and secrets, but your code needs to authenticate to Key Vault to retrieve them. Managed Service Identity (MSI) makes solving this problem simpler by giving Azure services an automatically managed identity in Azure Active Directory (Azure AD). You can use this identity to authenticate to any service that supports Azure AD authentication, including Key Vault, without having any credentials in your code. Refrence https://docs.microsoft.com/en-us/azure/active-directory/managed-service-identity/overview

How to enable the managed Identies for any azure resource( azure web application or Azure functions).
to demostrate I we will use Azure functions.
![alt text](https://www.google.co.in/images/branding/googlelogo/2x/googlelogo_color_120x44dp.png)
