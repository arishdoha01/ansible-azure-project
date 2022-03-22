# DevOps/SRE Project - Using Ansible , Azure Cloud VMs, and AzureDevops Pipelines

This is a sample project that shows how to use Ansible: 

   1) Creates a Linux Server in Azure, which is used as an Ansible "Controller" node
   2) Installs all required packages on the Linux server via command line (Ansible, Python, Azure)
   3) Configure Ansible Playbook YAML and Azure DevOps Pipeline YAML to deploy cloud infrastructure (Web App Service and SQL Database)
   4) Deploy code for sample Java web application

# Pre-Requisite

As a pre-requisite, we need to create a "free" tier Azure account on https://azure.microsoft.com/en-us/free/

This account will allow us to:

   1) Create our VM's and other cloud resources in https://portal.azure.com/
   2) Create our Azure deployment pipelines in https://dev.azure.com/
