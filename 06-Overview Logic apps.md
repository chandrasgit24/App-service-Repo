# Overview 
Azure Logic Apps is a cloud-based platform that helps you schedule, automate, and orchestrate tasks, business processes, and workflows. With Logic Apps, you can design and build scalable solutions for app integration, data integration, system integration, and more.

-  Here's what you can do when you automate email using Azure Logic Apps:
-  Automate email notifications when specific events occur (e.g., receiving a new email or a file being uploaded to storage).
-  Integrate multiple services like Office 365 Outlook, Gmail, Outlook.com, and SMTP.
-  Use built-in connectors to read emails, extract content, and send automated responses.
-  Monitor and log workflow execution for auditing and diagnostics.
-  Customize workflows using conditions, loops, and variables.

## **General Hierarchy**
Logic App Workflow: A Logic App consists of a trigger followed by one or more actions:

Trigger: Defines the event that starts the Logic App (e.g., “When a new email arrives” in Outlook).

Actions: Define what happens next (e.g., extract subject/content, send a new email, post to Teams, write to a database).

## **Run History** 
Each execution of a Logic App is recorded and viewable in the run history. This helps in debugging and understanding workflow behavior.

## **Lab Objective**
By the end of this lab, you will:
-  Create an Azure Logic App
-  Set a trigger to run every 1 minute
-  Send an email using Outlook or Gmail
-  Verify the email and view workflow run history

## **Pre-requisites**
-  An active Azure account (https://portal.azure.com)
-  A valid email account (Outlook or Gmail)
