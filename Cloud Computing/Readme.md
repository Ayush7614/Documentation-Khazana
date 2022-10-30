# What is cloud computing ?

Cloud computing is the management of computing services such as storage, servers, data, networking, etc. over the internet instead of any physical storage for better and effective functioning. 

# Jobs profile in Cloud computing ?

Cloud Developer
Cloud Security Engineer
Front-End & Back-End Developer
SysOps Administrator
Development Operations Engineer
Solutions Architect

# How to start with cloud computing 

1. Get Aware With Cloud Technology & Platforms

2. Understand the Cloud Computing Fundamentals

- Deployment Models
- Auto-scaling
- Clustering
- Data Storage Infrastructure
- DevOps

3. Work On Other Required Skills

Proficiency in Java, AngularJS, and/or Python
Bachelor’s Degree in Computer Science
OR a Bootcamp with open source experience
Computer Networking

4. Get Some Advanced Training

5. Earn Relevant Certifications

AWS
Azure
Google Cloud

6. Do Practical Implementation

7. Look Out for Job Opportunities

# The most popular cloud providers and platforms?


1. Amazon’s AWS

Market share: 32%
Main advantage: Largest breadth of available services at 175
Notable Clients: Netflix, Linkedin, Twitch, Facebook, Twitter

2. Microsoft Azure

Market Share: 18%
Main advantage: Cost-effective for larger companies and those already using Microsoft products
Notable Clients: eBay, Boeing, Samsung, BMW, Travelocity

3. Google GCP

Market Share: 6%
Main advantage: Strong support for open-source software and machine learning
Notable Clients: Verizon, Facebook, Linkedin, Twitch, Intel, Yahoo

# Guarding Your AWS Profile

As soon as you start working with AWS, the first day itself can excite you. You create an account and start launching instances or start utilizing some other AWS services. After a few days you open your account and find that a huge bill has been imposed on your bill dashboard. And you might think, how all of a sudden this charge has been made even when you haven’t used much of the services. Or you can even find several unauthorized access too in your account. So here is the solution. This mostly happens due to certain security breaches in your account. Some unauthorized access gets into your account and runs their heavy-heavy servers and leads to huge costing. To protect yourself from such hacks you need to harden your AWS account as soon as you create it. Hardening can secure your account from any unauthorized access.

Below stated are the best practices followed to secure the AWS account.

Providing accurate details while signing up in AWS
Setting a strong password
Enable Multi-factor authentication (MFA)
Using CloudWatch
Using access key
Setting up IAM user, group or role for least privilege


## Providing accurate details while signing up in AWS
During sign up there are all essential details taken to contact you along with your payment details. The email you give and whatever alternate email you provide are the only sources AWS uses to reach out to you. Make sure that you give accurate and active email IDs and give alias email too, so that if you are absent to attend the emails then some other person can receive the updates through the provided mail ID. Keep checking the notifications you receive from AWS to keep yourself updated.

## Setting a strong password
For securing the account, keeping a strong password is the most primary precaution one should take. It becomes very essential that the password should be very strong and mostly random. Generally random passwords are the hardest to be cracked. There are many sites available that generate random strong passwords. This is one of them which I use. And don’t forget to keep a note of the password whichever you choose.

## Enable Multi-factor authentication (MFA)
Using MFA to access the account makes it more secure. MFA is a 6 digit numeric code that MFA authenticator generates. It can be an application that can be installed on mobile or a hardware that can be attached to your system. The MFA code runs on one time password algorithm. After providing email and password, MFA needs to be entered to successfully login to your AWS account. A user cannot type a code from another user’s MFA device to authenticate. For every account the code is unique. Always create MFA for root as well as for all IAM users.

## Using CloudWatch
AWS CloudWatch is mainly used to meter the usage of the services. You can set a threshold for the use of a particular service and set an alarm to notify you through email (SNS email notification) or initiate certain action like start, stop or terminate an EC2 instance. Even Amazon EC2 scaling can be done using this feature. You can find the services that support CloudWatch metrics here. These all features can help you to get alert whenever the usage of certain parameter(s) go out of the threshold level. Apart from alerts it is also used for autoscaling, traffic handling, error handling, perform operations on metrics and log analytics as well.

## Using access key
Access key is to give programmatic access to the AWS resources from the command line and also to use AWS APIs. The key contains username, password, Access key ID, Secret access key and Console login link. Access keys should not be directly used from the root account rather IAM user should be created with limited permissions as per requirement. The access key csv file can only be downloaded when the key is created. If you don’t download or lose the access key then a new access key needs to be created. Only two keys can exit in an account at a time.

## Set up IAM user, group or role for least privilege
Access management can easily be done by using Identity and Access Management (IAM) to create users, groups and roles. Root account user can grant limited permission to the IAM users and groups. In the corporate world, whenever there is a requirement of giving access to any new user, group or for any role then the permission to handle the services can easily be done using IAM. Later on the access can be changed as per requirement.
