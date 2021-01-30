# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

# ANALYSIS
*For **both** a VM or App Service solution for the CMS app:*
# VM
- Costs = Lower upfront cost compared to purchasing and maintaning hardware, but over the time it may get more, more and more expensive
- Scalability = The VM can only get scalability, if there is multiple VMs grouped. In case of many VMs groupes, then there will be two options virtual machine scale sets and load balancers
- High Availability = if there is multiple VMs grouped
- Workflow = Iaas(Infrastructure as a service) that allows somebody to create and use virtual machine in the cloud

# App Service
- Costs = Varies based on the plan choosen which are Dev/Test, Production, and Isolated
- Scalability = Auto scaling, since it's possible to use Vertical and Horizontal scaling. On the one hand the Vertical Scaling increases or decreases resources allocated to our App Service and on the other the Horizontal Scaling increases or decreases the number of Virtual Machine instances our App Service is running
- High Availability
- Workflow = PaaS(Platform as a Service) that allows the developer to focus on the application or Azure takes care of the infrastructure

# CHOOSEN
- App Service

# JUSTIFICATION

I decided to choose that one, just because of the possibility of having Scalability all the time, differently from VMs where I'd need to have multiple VMs to come the scalibility. Besides, I also thought about the cost I would have, since a desadvantage from VMs is the cost that can be more expensive.


### Assess app changes that would change your decision.

I would just change my decision made if I had enough time to manage the deployment and infresctructure. Currently as a developer
I don't have enough time for both of them and that is why I will just take care of the deployment and Azure takes care of the infraestructure separetely