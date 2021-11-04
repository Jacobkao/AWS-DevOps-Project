# AWS-DevOps-Project


•	Spin up ec2 instances through infrastructure as code, Terraform.
•	Multi-region architecture infrastructure for High Availability and Disaster Recovery Purposes.
•	Applications run in docker containers to prevent errors and inconsistencies.
•	Automate AWS Code Pipeline which includes source, build, deployment, and manual approval when making new changes on the S3 bucket for ECS web service.
•	Infrastructure and application are under continuous monitoring with notification mechanism.


By this time the Custom code which we have in S3 is pushed to the ECS and served to the users through ELB as shown below.
Once you have uploaded, you will see, CodePipeline noticed the change in the source code and started a new release.
Let's now set up CloudWatch to monitor the Pipeline whenever a new deployment is triggered and emails the application owner through SNS
Now let’s build the same replication environment in the other region
We have successfully created the infrastructure, monitored it completely and ensured high availability by successfully deploying the application in two different regions
