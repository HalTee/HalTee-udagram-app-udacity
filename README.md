# Deploy a high-availability web app using CloudFormation

This project deploys web servers for a highly available web app using CloudFormation. It creates and deploys the infrastructure and application for an Instagram-like app from the ground up. It starts with deploying the networking components, followed by servers, security roles and software on AWS by following best practices.

Creating this project gave me the hands-on experience needed to confidently talk about infrastructure as code. A realistic scenario whereby a dummy application (a sample JavaScript or HTML file) was deployed to an Apache Web Server running on an EC2 instance.

The infrastructure was discarded as soon as the testing was completed and results were achieved.

There are two parts to this project:

Diagram: A visual aid to understand the CloudFormation script.
Script (Template and Parameters): This contains matching CloudFormation script

# Files included in the project and their functions:
- haleem_dairoproject2.yml = CloudFormation YAML file that contains the code for the creation of infrastructure
- proj2create.sh = Shell script for creation of Cloud formation stack on AWS
- proj2update.sh = Shell script for updating the created stack on AWS
- haleem_dairo_UdacityProject2diagram = The infrastructure diagram used to create the cloudformation file
- Captures(1-5) = Pictures of infrastructure created and result of tests carried out.