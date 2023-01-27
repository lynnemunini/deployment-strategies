# Udapeople App
This GitHub repository contains all the necessary files for the deployment and maintenance of the Udapeople application.

![Intro SVG](intro.svg)

### Files in this repository:

[Presentation](presentation.pdf)

Presentation in PDF format to explain to stakeholders the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.

[Cloudformation Scripts](/.circleci/files)

The necessary CloudFormation templates that will be used throughout the deployment phase.

[Ansible Playbooks and Roles](/.circleci/ansible)

Directory that contains the Ansible playbooks and roles that will be used throughout the deployment phase. The playbooks and roles are used to deploy the application to AWS.

[CircleCI config.yml file](/.circleci/config.yml)

The CircleCI config.yml file that will use CI/CD to deploy the application to AWS. 

[The backend](backend)

This directory contains the files for the backend of the application.

[The frontend](frontend)

This directory contains the files for the frontend of the application.

[Prometheus](.circleci/ansible/roles/configure-prometheus-node-exporter)

This directory contains the files for the Prometheus node exporter. This is used to monitor the application.
It will be used to Surface critical server errors for diagnosis using centralized structured logging.

## Usage

1. Review the Presentation.pdf to understand the fundamentals and benefits of CI/CD for the Udapeople application.
2. Update the cloudformation-scripts/ and ansible-playbooks-and-roles/ with the appropriate values for your deployment.
3. Configure CircleCI for your application using the .circleci/config.yml file.
4. Use the backend/, frontend/ and prometheus/ directories to build and deploy the application.

**Note:** Make sure you have the necessary permissions and configurations to access the AWS resources and CircleCI.
