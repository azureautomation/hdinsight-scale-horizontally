HDInsight: Scale Horizontally
=============================

            

**Scale-HDInsightClusterNodes** is a simple PowerShell workflow runbook that will help you automate the process of scaling in or out your HDInsight clusters depending on your needs.


The script receives 4 parameters:


**ResourceGroupName**: The name of the resource group where the cluster resides


**ClusterName**: The name of your HDInsight cluster


**Nodes**: The number of nodes you want for the cluster


**ConnectionName**: The name of your automation connection account


This Workflow requires the following powershell modules: AzureRM.Profile, AzureRM.HDInsight


 

 
 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
