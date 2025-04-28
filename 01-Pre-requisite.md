# Pre-requisites to Deploy a Web App Using Azure App Service
### 1. Access Requirements
- Valid CloudLabs Credentials – You must have an active Spektra Systems CloudLabs account with Azure access.
- Assigned Azure Subscription – CloudLabs provides a pre-configured Azure subscription for training.
- Required Permissions – Your lab account has Contributor access to deploy and manage Azure resources.
  

### 2. Azure Resources Pre-Configured in CloudLabs
The lab environment already includes:
- An Azure Active Directory (AAD) tenant for identity management.
- A Resource Group where you’ll deploy the App Service.
- Networking policies allowing outbound internet access for deployments.
  

### 3. Development & Deployment Requirements
- Web Application Code – You can use:
- A sample app (provided in the lab) or your own code.
- Supported languages: .NET, Node.js, Python, Java, PHP, or static HTML.
- Deployment Method (Choose one):
- GitHub/Azure Repos (for CI/CD).
- Direct ZIP deploy (manual upload).

Docker Container (if using containers).

## Lab Environment Notes
In this lab, we’ll use:
- Azure App Service (Windows/Linux) for hosting.
- GitHub/Azure Repos for deployment (alternatively, direct upload).
- Free App Service tier (can be scaled later).
