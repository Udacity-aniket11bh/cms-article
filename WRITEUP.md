# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- 
- App service will best fit our requirements for this project.
- For the CMS project, first of all we don't need access to the underlying VM and neither we need to deploy any configuration. Second, the app service is providing all the things pre installed like OS, languages, MySql server integration etc. And finally it doesn't make sense to use a complete VM for such small application. So, it makes sense to perfer a App Service over VM.

### Assess app changes that would change your decision.

If we prefer to change the decision to use a VM rather than an App service, then first of all we will need to deploy and install all the suitable applications, language features, db services to the VM. The cost will certainly go up, so we will need to keep that in mind. And finally, the config file in our app regarding db connection will also need to change.

cmsarticlestorageaccount
cms-article-anapp
cms-article-db
Pass(0rd