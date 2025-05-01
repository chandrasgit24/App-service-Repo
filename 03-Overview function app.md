# Overview : Triggering an Azure Function on Image Upload to Storage
In this lab, we will implement an Azure Function that automatically triggers when a new image is uploaded to an Azure Storage Account. The function will extract and log the name and size of the uploaded image file. This exercise demonstrates event-driven architecture using Blob Storage Triggers, a key feature of Azure Functions.

## **Objective**
To build a serverless function that listens to blob storage events and captures metadata (file name and size) of uploaded images in real time.

- Azure Function App – Hosts the function and provides a scalable, event-driven execution environment.
- Blob Storage Trigger – Monitors a specific container in Azure Blob Storage and triggers the function when a new file is uploaded.
- Azure Blob Storage – Serves as the storage backend where image files are uploaded.
- Application Insights – (Optional) Monitors and logs function executions for diagnostics and performance tracking.

## **Key Benefits Demonstrated**
- Real-Time Event Handling – Immediate response to file uploads without polling or manual checks.
- Serverless Execution – No infrastructure management required; scales automatically based on event volume.
- Cost Efficiency – Pay only for the compute used when the function is triggered.
- Extensibility – Can be enhanced to perform additional processing (e.g., image analysis, virus scanning, or notifications).

## **Summary**
- Real-Time Event Handling – Immediate response to file uploads without polling or manual checks.
- Serverless Execution – No infrastructure management required; scales automatically based on event volume.
- Cost Efficiency – Pay only for the compute used when the function is triggered.
- Extensibility – Can be enhanced to perform additional processing (e.g., image analysis, virus scanning, or notifications).
