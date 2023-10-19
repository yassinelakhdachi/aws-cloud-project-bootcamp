# aws-cloud-project-bootcamp
the source code I developed during an AWS Cloud Project Bootcamp. It showcases my skills in building and deploying applications on the AWS Cloud platform using various programming languages and configurations.

# week.0 tasks
## Creating my AWS Account && Set up an IAM user:
To create an AWS account, follow these steps:
+ Go to the AWS website (https://aws.amazon.com/) and click on the "**Create an AWS Account**" button.
+ Enter your email address and password, and click "Continue".
+ Fill out the required contact information and click "Create Account and Continue".
+ Provide your payment information to enable you to use AWS services that have associated charges. Some services offer a free tier to get started.
+ Follow the on-screen instructions to complete the account setup process, including verifying your identity and setting up security options.
+ 

![My AWS Account](/Docs/Assets/aws_account.png)

 Then I set up an **IAM user** to execute all my tasks. I even added Multi-Factor Authentication to enhance security, which I learned about in [**Ashish's Week 0 - Security Considerations**](https://www.youtube.com/watch?v=4EMWBYVggQI&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=15). 
 Here are short instructions to create an IAM user associated with your AWS account:
+ Log in to the AWS Management Console and go to the IAM dashboard.
+ Click "Users" and then "Add user".
+ Enter a user name, select "Programmatic access", and click "Next: Permissions".
+ Choose the appropriate permissions and click "Next: Tags" and "Next: Review".
+ Review the user's settings and click "Create user".
+ Download and securely store the user's Access Key ID and Secret Access Key.

![IAM user associated to my account](/Docs/Assets/aws_iam.png)


## creating a Billing alarm alert and set a budget to manage costs effectively:
In order to follow the best practices concerning the** pricing of AWS** services, I've followed the tutorial of [Chirag's Week 0 - Spend Considerations](https://www.youtube.com/watch?v=OVw3RrlP-sI&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=13), then created a Billing alarm alert, Here are the short instructions for creating a billing alarm on AWS:
+ Log in to the AWS Management Console and go to the CloudWatch service dashboard.
+ Click on "Alarms" in the left-hand menu and then click "Create alarm."
+ Select "Billing" as the metric type and choose the "Total Estimated Charge" metric.
+ Set a threshold for the billing amount and configure the notification settings.
+ Review the alarm settings and click "Create alarm."

![Billing Alarm](/Docs/Assets/billing_alarm.png)

I set an AWS budget of** $3 per month** for my project, following these short instructions:

+ Log in to the AWS Management Console.
+ Click on "Billing and Cost Management".
+ Click on "Budgets".
+ Click "Create budget".
+ Choose "Cost budget".
+ Set the budget amount to $3 and choose "Monthly" as the budget period.
+ Name your budget and select notification preferences.
+ Click "Create".

![Billing Alarm](/Docs/Assets/Bootcamp_Budget.png)


## Installing AWS CLI, and get familiarized with AWS CloudShell:
I also installed the **AWS CLI** on my computer, The role of AWS CLI is to provide a command-line interface for interacting with various AWS services and resources, enabling users to manage their AWS infrastructure and automate their workflows from the terminal:

![Billing Alarm](/Docs/Assets/aws_cli.png)

 and got familiar with AWS CloudShell to generate my AWS Credentials:
 
 ![Billing Alarm](/Docs/Assets/Generate_Credentials.png)
 
Practicing using **AWS CloudShell** is essential to mastering it. As a Linux shell environment with pre-installed tools and libraries, it will allows me to perform various AWS operations such as managing **EC2 instances**, **S3 buckets**, and **Lambda functions** using the AWS CLI, Git, and Python. Regularly practicing with CloudShell will help me become more proficient with these tools, enabling to quickly and efficiently manage my AWS resources. This hands-on experience will also help me become more familiar with the AWS ecosystem, and how to leverage its capabilities to their advantage.


## creating a Logical Architectural Diagram for my app in Lucid Charts:
Creating a **logical architecture diagram** for my app in **Lucidchart** was an effective way to visualize and communicate the different components and interactions within my application, in my case I used **AWS Architecture 2021 shapes** to represent different elements of my application, and lines to show the flow of data and interactions between them: 

![Logical_Architecture_Diagram](/Docs/Assets/architecture_diagram.png)

Here is the link to my Logical Architecture Diagram: [Logical_Architecture_Diagram](https://lucid.app/lucidchart/4c72a1e1-4824-43eb-93f5-4e93a0e53e8e/edit?viewport_loc=-1219%2C-11%2C2750%2C1276%2C0_0&invitationId=inv_fd78f6b7-dc8e-4a31-8c2f-c2494d3b37d2)

Moving forward, I'm excited to explore more AWS services using my own architectural diagram to get even more comfortable with the platform.






 
 
 
 
 
 
 
 
 
