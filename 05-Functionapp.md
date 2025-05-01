# Exercise 1: Implementing an Azure Blob-Triggered Function to Log Image Name and Size
## Objective
In this lab, you will implement an Azure Function that automatically triggers when a new image is uploaded to an Azure Blob Storage container. The function will extract and log the file name and file size of the uploaded image.This guide uses Azure Portal only.

## Pre-requisites
- Access to Azure Portal via CloudLabs or personal subscription.
- Contributor role assigned to your account.
- A Resource Group available to deploy resources.

### **Task 1: Create a Storage Account**
Azure Storage is a Microsoft-managed service providing cloud storage that is highly available, secure, durable, scalable, and redundant. Azure Storage includes Azure Blobs (objects), Azure Data Lake Storage Gen2, Azure Files, Azure Queues, and Azure Tables. The cost of your storage account depends on the usage and the options you choose below

In the Azure Portal, click "Create a resource". Search for "Storage account" and select it.

Click "Create".

Fill in the details:

Subscription: Select the active one.

Resource Group: Choose an existing one or create a new one.

Storage account name: e.g., imgstorlab123 (must be globally unique).

Region: Choose the closest region.

Leave other options as default.

Click "Review + create", then "Create".
