# Pre-requisites to Implement an Azure Blob-Triggered Function App
### 1. Access Requirements
- Valid CloudLabs Credentials – You must have an active Spektra Systems CloudLabs account with Azure access.
- Assigned Azure Subscription – CloudLabs provides a pre-configured Azure subscription for hands-on labs.
- Contributor Role – Your lab account must have Contributor permissions to create and manage Azure resources, including Function Apps and Storage Accounts

### 2. Azure Environment Setup
The lab environment includes the following pre-configured resources:
- Azure Active Directory (AAD) – For authentication and role-based access control (RBAC).
- Resource Group – A designated resource group to host the Function App and related services.
- Networking Policies – Outbound internet access is enabled for Azure Functions and Storage communication.

### 3. Azure Services Required
- Azure Storage Account
- Must include a Blob Container for image uploads.
- Configure access (public or private with appropriate Function App access).

- Azure Function App
- Runtime stack: Choose from supported languages (Node.js, Python, C#, etc.).
- Hosting plan: Consumption Plan (default and cost-efficient for event-based execution).

- Application Insights (Optional) – For logging, monitoring, and diagnostics.

### 4. Development & Deployment Requirements
- Development Tools
- Visual Studio Code with Azure Functions extension (recommended) or Azure Portal for inline function creation.
- Azure CLI or Azure PowerShell (for scripting and resource provisioning).

- Function Code
- A function that uses a Blob Trigger to detect new uploads.
- Logic to extract and log the blob’s metadata (name and size).

- Deployment Methods
- Azure Portal (inline editor or upload).
- VS Code with Azure Functions extension.
- GitHub Actions or Azure DevOps (for CI/CD pipelines).

### 5. Lab Environment Notes
In this lab, we will:
- Use Azure Blob Storage to upload image files.
- Implement an Azure Function App with a Blob Trigger.
- Log image name and size using Application Insights or the Azure Monitor logs.
- Operate within the Consumption Plan for scalability and cost optimization.
