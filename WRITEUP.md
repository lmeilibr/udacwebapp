# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

The App Service was the choice for deploying the app, due to the lightweight
Flask App, Python being one of the supported languages. The free tier for dev/test
is also an attrative for this project. Another benefit is the PaaS, which reduces the
labor cost of maintaining and taking care of the VM/OS, making the workflow much simplier.
For scalability and availability both VM and App Service are very similar.

### Assess app changes that would change your decision.

If a non-supported language, like Go, shall be used instead of Python, then
a decision to use VM would be considered. As the app grows, needing more RAM
and CPU, the choice to go to VM would also be considered.