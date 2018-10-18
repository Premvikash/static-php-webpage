# Its simple appengine project to be used under google cloud to have one html page running

Set the project name locally in my case its prem-u
``` 
$gcloud config set project prem-u
``` 

Create the appengine to be used for deployment
``` 
$gcloud app create
``` 

Deploy the app.yaml file into above created appengine in project prem-u
``` 
$gcloud app deploy app.yaml --project prem-u
``` 

To check logs
``` 
$gcloud app logs tail -s default
``` 

To browse the deployed application in browser
``` 
$gcloud app browse
``` 

