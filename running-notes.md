step1:
Generate a new token and assign the necessary permissions, such as ‘repo’ to access repositories.


step2:::

Install Necessary Plugins:
Open Jenkins Dashboard: Log in to your Jenkins interface.
Navigate to “Manage Jenkins > Plugins”.
Install Plugins: Look for the “docker pipeline” and “sonarqube scanner” 
plugins install them and restart Jenkins if required.

step3:

Configure Your Pipeline:

Click on the created job and scroll down to the “Pipeline” section in the configuration screen.
Choose “Pipeline script” or “Pipeline script from SCM”.