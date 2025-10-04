Terraform Projects

This repository contains multiple hands-on projects showcasing Infrastructure as Code (IaC) using Terraform.
Each project is provisioned with its own configuration and documentation.
________________________________________________________________________________________________________

📂 Projects
1. Day 1 – Basics
Introduction to Terraform basics, providers, and resources.
📁[day1](./day1)
________________________________________________________________________________________________________

2. Day 2 – VPC Setup
Creating a Virtual Private Cloud (VPC) with subnets, route tables, and internet gateways.
📁 [day2-vpc] (./day2-vpc)
________________________________________________________________________________________________________

3. Day 3 – Modules
4. Using and organizing Terraform modules for reusable infrastructure.
5. [📁day3](./day3)
________________________________________________________________________________________________________

4. Day 4 – Provisioners
Provisioning resources and running scripts on instances with Terraform provisioners.
 [📁day4-provisioner](./day4-provisioner)
________________________________________________________________________________________________________

5. Vault Integration
Integrating HashiCorp Vault with Terraform for secret management and policy enforcement.
 [📁vault-terraform](./vault-terraform)
________________________________________________________________________________________________________

🚀 Upcoming Projects:
EKS with Terraform – Deploying Kubernetes cluster on AWS.
Ansible with Terraform – Hybrid automation with Terraform + Ansible.
________________________________________________________________________________________________________

🛠️ How to Use:
1. Clone this repository:
     git clone https://github.com/siham-bkz/terraform.git
     cd terraform
2. Navigate to the project folder you want:
     cd day4-provisioner
3. Initialize and apply:
    ```bash terraform init
     terraform apply ``
________________________________________________________________________________________________________

📖 Notes:

 . Each project has its own README.md with setup and explanation.
 . Make sure you have:
     .Terraform installed → [Install Terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

     .AWS CLI configured →
     ```bash aws configure ```
                                                                                                                  
    




