Azure Stack VM GUI Beta 1 for MAS TP2
=====================================

            

I hope you have had time and oppotunity to try out the new Azure Stack POC.


In Azure Stack the VMs are named by their GUID in Hyper-V. This makes perfect sense, since multiple tenants could easily name their VMs the same name.


 


But when administrating your hyper-v host, It can be a bit hard to recognize which machine is which.


Therefore I have create a small GUI tool in PowerShell to help list the machines on a host, and to be able to trigger some basic actions.


This is the first beta and the following actions have been added:


  *  Connect to Console 
  *  Stop VMs 
  *  Start VMs 

 


**NB! Please bear in mind that this is a beta tool and it is not meant for production (neither is Azure Stack).**


** ![Image](https://github.com/azureautomation/azure-stack-vm-gui-beta-1-for-mas-tp2/raw/master/image_thumb-34.png)**


** **

 

**




 


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
