# ToDo API realisiert mit PaaS (dummy backend)

## Before you begin
1. Open VS Code
2. Clone the following repo from Github:  https://github.com/modul346/paas-todoapi-dummy-backend.git
3. Put it into the folder where you keep all the other projects of this module


## Steps for Setup in AZURE
1. Create Resource Group with the name PaaS in the Region Switzerland North
2. Create Web App (AppServices) within the Resource Group PaaS
3. Choose a unique name
4. Select Publish Code
5. Runtime Stack .NET 6 (LTS)
6. Operating System Windows
7. Leave the rest with default settings
8. Create Web App
9. Check that Website is running
10. Get the URL of your WebApp (Overview) and copy it to the Clipboard
11. In VS Code apitest.http change the hosturl to this value
12. Now it is time to deploy the API to Azure!
13. Open the AZURE tools on the left.
14. If you are not logged in log in
15. Hover over WORKSPACE (bottom left) and then click the deploy item
16. It asks what to deploy: Choose WebApp
17. Allow the configurations files to be written
18. Wait until the app is fully deployed
19. Test your API with apitest.http