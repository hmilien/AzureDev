# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
   a) VM will cost more than APP service.
   b) App Service can scale horizontally and vertically. VM as well by adding more CPU or load balancing the app with multiples VM. 
      App service are easier to scale
   c) Availability is not an issue for either solution.
   d) App services might be more practical in a DevOps perspective. Easier to deploy

- *Choose the appropriate solution (VM or App Service) for deploying the app*
  We will use an app service
- *Justify your choice*
This app is pretty simple and does not need a dedicated machine at least at the begining. 
In the future if more resources are needed, it will be easy to add more.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
In the future, If we consider improving the app and use more adavanced framework like python 9 that are not supported
for now in App Service