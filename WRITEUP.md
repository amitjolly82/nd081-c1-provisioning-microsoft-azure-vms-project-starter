# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

APP SERVICE: The CMS app is lightweight and don’t need much compute resources. Azure pricing for such use case is reasonable. App service provides seamless deployment experience using GitHub. The developer and testers can focus on functionality and App Service insulates from deployment complexities. As like other Azure services the application can be analyzed and scaled seamlessly. 

VM: The costs, scalability, and availability for a CMS app deployed through a VM are also reasonable. The VM allows for more customization of the app's capability. VM will allow more customizations as appropriate. The developer can control, and fine tune resources based on their application needs. The VM can be scaled both horizontally and vertically.

My Choice: I will go with AppService for CMS app. CMS app is lightweight and doesn’t need heavy computing resources. The AppService provides Python environment to run and alleviates deployment complexities. If the application usage grows AppService provides easy scaling options. AppService offers robust scalabliy and availablity like VM with ease of use.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 