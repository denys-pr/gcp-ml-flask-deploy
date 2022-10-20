# gcp-ml-flask-deploy

This is a learning project to auto-deploy apps to Google Cloud Platform

There are four parts:
- Flask app 
- app.yaml 
- cloudbuild.yaml
- requirements.txt

How to use:
- Setup trigger in Cloud Build service to trigger builds on main branch changes
- Make sure in cloudbuild the settings are enabled for App Engine Admin and Service Account User
- Push any change into main branch and observe that it triggers an auto-deploy
