# Exercise 1: Create a Logic App that Trigers and Sends an email to yourself with the message: "Hello from Logic Apps"!

## Step 1: Sign in to Azure Portal
1. Open a Chrome browser and go to: https://portal.azure.com. Log in using your Azure credentials.
   ![](Images3/1.png)
   
1. In the Search bar at the top, type: Logic Apps and press Enter. Click Logic Apps from the list. Click + Create.
   ![](Images3/2.png)
   
1. Fill the required fields as mentioned below: After that click on review+create

   | Field          | Value                        |
   | -------------- | ---------------------------- |
   | Subscription   | (Select your subscription)   |
   | Resource Group | select existing (e.g., `LogicRG`) |
   | Logic App Name | `SendEmailApp`               |
   | Region         | East US      |
 
     ![](Images3/5.png)
   
1. After clicking review+create your deployment will be completed as shown below, Once deployment is done, click Go to Resource In the new page.
   ![](Images3/6.png)

1. In the overview click Logic App Designer Scroll down and select Blank Logic App
    ![](Images3/7.png)

1. Now in the logic app designer Add a Trigger In the Logic App Designer, search for Recurrence Select Recurrence (Schedule)
    ![](Images3/8.png)

1. Enter the interval as 1 and Frequency in Minutes and click on save
   ![](Images3/9.png)
