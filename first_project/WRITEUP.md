# Write-up

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

These are the important points to consider whether to choose Azure VMs or Azure App Service:

- Azure VMs are more expensive to run in comparison to Azure App Service.
- Azure App Service have constraints in comparison to Azure VMs in terms of scalability. Hence, Azure VMs are preferred for apps, which have scope to expand for future.
- Azure App Service requires much less managerial efforts in comparison to Azure Virtual Machines.
- The development of app is much simpler and faster in Azure App Service.
- Azure VMs offer developer more control over the environment. Like, one can’t choose underlying OS of VM in an Azure App Service.
- Azure App Services do not offer Pay-as-you-Go. Hence, you’re paying for the service plan, even if you’re not using it.
- There may be constraints for the support of certain programming languages on Azure App Service. In that case, one has to use Azure VM to create environment for the programming language.
- on both choices you don’t have to worry about the initial investment required to buy the hardware itself, you don’t have to maintain it and think about its 24 hours, 365 days availability

I chose the App Service as it is cost efficient for our lightweight app, makes the deployment easy and keeps the administration at a minimum.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the app needs to be updated for more compute power, maybe playing movies or editing images or something that would require more hardware it might be cheaper to choose VM. Also if there was functionality desired that is not supported by Azure i would also choose the VM. 
Being unable to manage the software on the server may also cause significant issues might become a problem.

