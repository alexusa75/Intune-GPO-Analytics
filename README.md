# Intune Group Policy Analytics - Find duplicates and conflicts

With this script, you can export all Intune imported GPO to a csv file and get some fields to filter the **duplicates** and **conflicts** on all your GPO settings.

## If is the first time running the script you should run the following commands:
```powershell
#Import Microsoft Graph Intune Module
Install-Module Microsoft.Graph.Intune

# Connect to MsGraph and provide admin consent
Connect-MSGraph -AdminConsent

