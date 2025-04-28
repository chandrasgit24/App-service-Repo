# Pre-requisites to Deploy a Web App Using Azure App Service

To deploy a web app on Azure App Service, you need the following:
- An Active Azure Subscription
  You must have a valid Azure subscription (Pay-As-You-Go, Free Trial, or Visual Studio Benefits).

If you don’t have one, you can create a free Azure account.
- Required Permissions
  Contributor or Owner role on the Azure subscription (to create & manage resources).

If using Azure Active Directory (AAD) for authentication, ensure you have permissions to register apps.
- Code or Sample Application
  A web application (e.g., .NET, Node.js, Python, Java, PHP, or static HTML).

You can use:
A sample app from GitHub (e.g., Azure Samples).
Your own local code repository.
A Docker container (if deploying as a containerized app).

# Lab Environment Notes
In this lab, we’ll use:
- Azure App Service (Windows/Linux) for hosting.
- GitHub/Azure Repos for deployment (alternatively, direct upload).
- Free App Service tier (can be scaled later).
