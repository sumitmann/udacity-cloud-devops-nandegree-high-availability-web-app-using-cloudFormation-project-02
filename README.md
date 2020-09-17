# Project 2 - Deploy a High Availability Web App using CloudFormation 

![Udagram app diagram](Diagram-of-the-Udagram-App.jpeg)

> In this project, I deployed web servers for a highly available web app using CloudFormation.

## Files included:
```sh
* Diagram-of-the-Udagram-App.jpeg : AWS infrastructure diagram
* create.sh : Cloudformation create stack script 
* update.sh : Cloudformation update stack script
* destroy.sh : Cloudformation delete stack script
* infrastructure.yml : Udagram Project's CloudFormation script
* parameters.json : Udagram Project's CloudFormation script parameters
```
## Run below command to deploy:

```sh
> ./create.sh UdagramApp infrastructure.yml parameters.json