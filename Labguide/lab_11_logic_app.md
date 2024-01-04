# Lab 11 - Integrate Logic App with Threat Protection and XDR

## Lab scenario

The integration of a Logic App with Threat Protection involves configuring triggers and actions to receive alerts, while interaction with XDR solutions requires adding actions to exchange data, perform analyses, and trigger responses. Implementing conditional checks and logic within the Logic App allows for tailored handling of received threat information, ensuring effective responses and workflow execution before thorough testing and deployment to production environments. 

## Lab objectives
 In this lab, you will perform the following:
 - Task 1: Create an Azure logic app
 - Task 2: Integrate logic app with Microsoft Defender for Cloud for threat notification.
## Estimated timing: 60 minutes

## Architecture Diagram

## Exersise 1: Integrate Logic App with Threat Protection and XDR

### Task 1: Create an Azure logic app

1. In the Azure portal, search for and select **Logic App** and, on the **Logic Apps** blade, select **+ Add** the select **Consumption**.

1. On the **Basics** tab of the **Logic App** blade, specify the following settings (leave others with their default values):

    | Setting | Value | 
    | --- | --- |
    | Subscription | the name of the Azure subscription you are using in this lab |
    | Resource group | select the existing resource group from drop down |
    | Logic App name | **PostMessageTeams-OnIncident** |
    | Region | Select region where you want to deploy logic app |
    | Select the location | select the location where resource group is deployed. |
    | Plan type | **Consumption** |

1. Select **Review + create** and then select **Create**. 

### Task 2: Integrate logic app with Microsoft Defender for Cloud for threat notification.

1.Select the 

