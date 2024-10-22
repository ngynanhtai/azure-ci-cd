[![Python application test with Github Actions](https://github.com/ngynanhtai/azure-ci-cd/actions/workflows/main.yml/badge.svg)](https://github.com/ngynanhtai/azure-ci-cd/actions/workflows/main.yml)

# Overview

A Flask Web App implements Continuous Integration & Continuous Delivery

## Project Plan

A link to a Trello board for the project: [Trello](https://trello.com/b/4ispJp93/udacity-project)

A link to a spreadsheet that includes the original and final project plan: [Project Plan](https://docs.google.com/spreadsheets/d/1W7-2dZRL0NmAcCXBJ_DMLMAVCHSuuxOiBartLt40X3E/edit?usp=sharing)

## Instructions

* Architectural Diagram (Shows how key parts of the system work)
![image](https://github.com/user-attachments/assets/d2f339e7-0d13-4739-b0e3-a80625075114)

* Project running on Azure App Service
![image](https://github.com/user-attachments/assets/b2248c23-919c-4665-b797-953cd005efb5)

* Project cloned into Azure Cloud Shell
![image](https://github.com/user-attachments/assets/10367c04-3368-406d-96a9-e79f26935982)

* Passing tests that are displayed after running the `make all` command from the `Makefile`
![image](https://github.com/user-attachments/assets/ad2b892e-5844-4ee7-b263-8a13de802719)

* Output of a test run
![image](https://github.com/user-attachments/assets/74907acf-8a3b-435b-adad-a8a806fe3b91)

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).
![image](https://github.com/user-attachments/assets/b6142916-568a-4ae6-8dc5-d2be5e9779b4)

* Running Azure App Service from Azure Pipelines automatic deployment
![image](https://github.com/user-attachments/assets/731663ad-dfe0-4e95-804a-94214c31982f)


* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```
![image](https://github.com/user-attachments/assets/0366b8d8-605c-41d7-b586-fa7584fddaff)


* Output of streamed log files from deployed application
![image](https://github.com/user-attachments/assets/f273e7a3-1828-4449-ac0a-5796995e5961)

> 

## Enhancements

- Adding load balancer
- Seperate multiple environments
- Avoid automatically trigger CI
- Automated test

## Demo 

Video Demo: [Youtube Link](https://youtu.be/0q-yT4lSpTc)


