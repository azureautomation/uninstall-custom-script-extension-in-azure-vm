Uninstall custom script extension in Azure VM
=============================================

            

 

 

This runbook uninstalls the custom script extension from the Azure VMs brought up by ASR (Azure Site Recovery) failover. This runbook is to be used in the context of ASR recovery plans for workloads hosted on StorSimple devices. This is required so
 that in failover -> failback -> failover scenario, the custom script extension can trigger the iSCSI script.


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
