# Test Coverage
## Deployment:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/flosum-service/test-coverage)

## How to configure Test Coverage

#### Step 1: Creating the Heroku application
Go to the GitHub account provided by your Customer Success team. 
Go to the repository “test-coverage”. 
Click the button "Deploy to Heroku" to deploy the application to Heroku. (See Fig. 1.) 

![GitHub Logo](./assets/img/Fig1.png)
<p style="text-align: center"><span>Fig. 1</span></p>

 
Enter application name  you want to give to this Heroku app and click the button “Deploy app”.
 

![GitHub Logo](./assets/img/Fig2.png) 
<div style="margin: auto"> Fig. 2</div>
 
This should result in the successful deployment of the code in the GitHub repository to the Heroku app. 
 
#### Step 2: Creating “Named Credentials”
In Heroku, select Name app. Next go to the application settings page and copy the domain. (See Fig. 3.) 

![GitHub Logo](./assets/img/Fig3.png)
<p style="text-align: center">Fig. 3</p>
 
Now in Flosum select the Setup Gear. In the Quickfind box, search for "Named Credenitals". Then you will add a new Named Credential. Name : Flosum_Test_Coverage.  The URL is the domain that you just copied from Heroku. (See Fig. 4.) 

![GitHub Logo](./assets/img/Fig4.png)
<p style="text-align: center">Fig. 4</p>