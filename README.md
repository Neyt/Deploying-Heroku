# Deploying-Heroku
 Deploying to a hosting service with Heroku
Steps to deployment
Here's an overview of the steps you'll need to complete. We'll be going over each one in more detail.

Check your server code into a new local Git repository.
Sign up for a free Heroku account.
Download the Heroku command-line interface (CLI).
Authenticate the Heroku CLI with your account: heroku login
Create configuration files Procfile, requirements.txt, and runtime.txt and check them into your Git repository.
Modify your server to listen on a configurable port.
Create your Heroku app: heroku create your-app-name
Push your code to Heroku with Git: git push heroku master
