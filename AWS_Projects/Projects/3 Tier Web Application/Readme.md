# Deploying a 3 Tier Architecture On AWS using RDS Aurora Read/Write Replica
In this project, we are going to be building a 3 Tier Web Application. In this project, the goal is to create a highly resilient website which can quickly auto-scale with respect to the incoming traffic & Use the best security practices for Access control to various resources. The web tier will be public facing EC2 instances to which the public will get access to with the help of External ALB. From the Web tier, the traffic will be routed internally to App tier Private Instances using Internal Load balancer.

We will be using IAM roles for EC2 to use S3 & SSM. Then we will be creating various network resources in one click in the VPC instance & create 5 Security groups for External Facing Load balancer, Web tier EC2, Internal Facing Load balancer, App tier Private instances & DB. Aurora RDS DB will be created with Multi-AZ read/write replica module for high scalability & availability of the Database.


## Objectives:
•	Highly scalable, highly available, & fault-tolerant.

•	Using custom VPC instead of default ones.

•	Secure & apply best practices of IAM & security.


## Architecture
![AWS 3 Tier Architecture Diagram](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/ad9d8660-1ceb-4c7b-b7ae-3755fa1522a5)


## Services Used:
1.	IAM Role
2.	S3
3.	3 NAT Gateways
4.	3 Elastic IPs
5.	S3 Endpoint
6.	9 Subnets
7.	IGW
8.	1 Public 6 Private Route Tables
9.	RDS
10.	5 SGs
11.	EC2 (5-10)
12.	ALB - 2
13.	ASG - 2
14.	TG - 2
15.	Template -2
16.	AMI - 2
17.	Snapshots Auto Created

## Step by Step Guide:
Go through my "Deploy a 3 Tier Architecture On AWS  -  Soln.pdf" for a thorough walkthrough.

## Outcome:
Website created along with Database connection. The website is resilient, highly autoscalabale, load distributed traffic with the required security measures.

![Picture1](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/ccaaf4c1-2919-4850-8708-86a2047100c3)

![Picture2](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/4b6bd463-565d-4823-a9c4-1dac22fdf2eb)

![Picture3](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/3c9b710a-96d0-4e69-bbfa-6330897e0815)


## Resources to Clean-Up:
![Resources to clean](https://github.com/Pratheek1999/Cloud-DevOps/assets/46183408/57cecb71-0046-468e-ae7e-a41ef3fb17c6)

