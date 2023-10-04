## Deploying End-to-End Serverless AWS Web Application using Amplify & DynamoDB
In this project, we are going to create an End-to-End Serverless AWS Web Application using Amplify & DynamoDB. This means that instead of Traditional creation of EC2 web servers, we will be just focusing on creating our web app & then by using the AWS Amplify service we will deploy & host that Web App to the internet, thus taking out the server management task from the developer (hence serverless). 

We will use API Gateway to create REST APIs which will be used to trigger the AWS Lambda function (for doing the Output calculation). This lambda function will then use IAM roles to access/store the results in DynamoDB & then return the values through REST API to the Webpage.

## Objectives:
![image](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/895e3210-b782-4727-9fa5-7aefc33c3abf)

## Architecture
![AWS Cloud Architecture - Math_Web-App](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/64c439b9-2573-4b9d-887c-d65e8a2fd50c)

## Services Used:
![image](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/b4a1c3b4-3c04-463d-a253-a4e3c17a9366)

## Step by Step Guide:
Go through my "Math App Web Soln.pdf" for a thorough walkthrough.


## Outcome:
WebApp created using AWS Amplify. It is hosting the Web App using all the provide components.


Webpages:
![Webpage](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/13cbd22b-f5f5-47dc-a150-0d53f4a4b1ac)


![Webpage_2](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/0ea93f42-0861-4b41-84fa-32a5e41107f0)


DynamoDB results stored
![DynamoDB](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/bb3e7e65-0b16-4571-b819-e6854604eb96)


## Resources to Clean-Up:

![Resources to Clean-Up](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/2705f791-0a00-4b36-9a2b-c6856539131f)


