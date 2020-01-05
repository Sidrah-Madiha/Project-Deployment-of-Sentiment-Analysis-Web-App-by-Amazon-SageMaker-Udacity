# Project Overview: SageMaker Deployment Project

The notebook and Python files provided here, results in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project uses SageMaker, to deploy the model on a website so that it can be used by end user.

# Installation
 
 For this you need to have a AWS account:
 
 - Log in to your aws account.
 - In Services, search and click on Amazon SageMaker
 - On sidebar click Notebook instances.
 - Click Create Notebook Instances 
 - On next screen, use ml.m4.medium as computation instance > Create a role, also make sure the notebook instance have access to S3 resources, which it does by default. In particular, any S3 bucket or object with sagemaker in the name is available to the notebook.
 - Scroll down and click Github Reporsitory option > select "Clone a public Git repository to this notebook instance only" in dropdown and then add this URL: https://github.com/Sidrah-Madiha/Project-Deployment-of-Sentiment-Analysis-Web-App-by-Amazon-SageMaker-Udacity.git
 - Click Create
 - After a while the notebook will be created, click "SageMaker Project.ipynb" to open the project. The rest of the project details are present in the notebook itself.

