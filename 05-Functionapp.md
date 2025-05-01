# Exercise 1: Implementing an Azure Blob-Triggered Function to Log Image Name and Size
## Objective
In this lab, you will implement an Azure Function that automatically triggers when a new image is uploaded to an Azure Blob Storage container. The function will extract and log the file name and file size of the uploaded image.This guide uses Azure Portal only.

## Pre-requisites
- Access to Azure Portal via CloudLabs or personal subscription.
- Contributor role assigned to your account.
- A Resource Group available to deploy resources.

### **Task 1: Create a Storage Account**
Azure Storage is a Microsoft-managed service providing cloud storage that is highly available, secure, durable, scalable, and redundant. Azure Storage includes Azure Blobs (objects), Azure Data Lake Storage Gen2, Azure Files, Azure Queues, and Azure Tables. The cost of your storage account depends on the usage and the options you choose.

1. In the Azure Portal search bar, click "Create a resource". Search for "Storage account" and select it.
   ![](Images2/1.png)

1. In 2nd Step Click on create "Create".
   ![](Images2/2.png)
   
1. Fill in the details: In basic Tab
-  Subscription: Select the active one.
-  Resource Group: Choose an existing one or create a new one.
-  Storage account name: e.g., imgstorlab123 (must be globally unique).
-  Region: Choose the closest region.
-  Leave other options as default.
-  Click "Review + create", then "Create".
   ![](Images2/3.png)
   
-  Wait for your Deployment to complete and you will see the pop up displaying like below Your deployment is completed.
   ![](Images2/5.png)

   
### **Task 2: Create a Blob Container**
1. After deployment, go to the Storage Account. In the left menu on the overview section, click "Containers" under Data storage.
   ![](Images2/6.png)
  
2. Name it e.g., images, and set Public access level to Private.Click "Create".
   ![](Images2/7.png)



  
Create a function app, which lets you group functions as a logical unit for easier management, deployment and sharing of resources. Functions lets you execute your code in a serverless environment without having to first create a VM or publish a web application.
