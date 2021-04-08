# Write-up

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Both services are pretty comparable in price, scalability and availability. But for our leightweight app which doesn't need much compute power the App Service is slightly cheaper.
While choosing a VM the developer is able to customize and optimize the VM to his needs but also fully responsible for updating and servicing the OS.
This might come in handy when we have an app which is not supported by App Service.
On the other hand a big benefit of the App Service is the use of GitHub workflows on the Azure portal for continous deployment. With the App Service you are not responsible for OS updates or services which saves you some time and effort.

I chose the App Service as it is a bit more cost efficient for our lightweight app, makes the deployment easy and keeps the administration at a minimum.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the app needs to be updated for more compute power, maybe playing movies or editing images or something that would require more hardware it might be cheaper to choose VM. Also if there was functionality desired that is not supported by Azure i would also choose the VM. 
Being unable to manage the software on the server may also cause significant issues might become a problem.