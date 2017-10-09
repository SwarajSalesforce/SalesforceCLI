# SalesforceCLI
Download the FileUploader Components.zip file from this repository to your local org.

#Step 1 Heroku Installation:-
Depending on your OS version you can install the Heroku  toolbelt on your machine .The URL for the download is below

https://toolbelt.heroku.com/

Step 2 - Login via Command Line 
Once you install ,you can use your Heroku credentials to login in .If you have not signed up for heroku ,you can sign up for one online 

<img width="600" alt="install salesforce cli" src="https://user-images.githubusercontent.com/18612751/31323824-5a17dd50-acca-11e7-9b93-dff209f324dc.PNG">

Step 3 -Install the Lightning CLI Plugin
This can be installed by running following command once you login into heroku CLI
heroku plugins:install salesforce-lightning-cli

Step 4 -Navigate to your project path where you have your lightning component project on your local drive which you downloaded .\
If you are on windows simply CD into the project path with cd /.path

<img width="935" alt="cli run" src="https://user-images.githubusercontent.com/18612751/31323930-ffb47ffc-acca-11e7-8e7d-6dded9afcfeb.PNG">

## Find Issues

heroku lightning:lint .
