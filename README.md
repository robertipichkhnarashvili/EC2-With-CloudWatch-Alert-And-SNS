This repository contains a Terraform project that provisions EC2 instances using Terraform modules and sets up monitoring and alerts via AWS CloudWatch and SNS.

Project Overview


EC2 Instances: Created using Terraform modules for better modularity and reusability.


CloudWatch Agent: Installed on the EC2 instances to collect metrics like CPU, memory, and disk usage.


CloudWatch Alarms: Configured to trigger when CPU utilization exceeds a defined threshold.


SNS Notifications: Integrated with CloudWatch alarms to send email notifications when thresholds are breached.


To use this project run(have terraform and git preinstalled and git):

1. git init

2. git clone <repository_url>

3. terraform init

4. terraform apply