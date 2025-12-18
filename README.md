# Terraform – Complete Guide (Git/README)

 ## What is Terraform?
- Terraform is an Infrastructure as Code (IaC) tool developed by HashiCorp. It allows you to define, provision, and manage infrastructure across cloud providers (AWS, Azure, GCP) and on‑prem environments using a declarative configuration language.

   - **Infrastructure as Code**
   - **Multi-Cloud Support**
   - **Automation & Speed**
   - **State Management**
   - **Plan Before Apply**
   - **Reusable Modules**
   - **Version Control**
   - **Cost & Resource Optimization**
   - **Time saving**

 ## Terraform Installation?
 - Install Terraform on Windows
   - Download Terraform from:https://developer.hashicorp.com/terraform/downloads.
   - Extract **terraform.exe**
   - Add Terraform to **System PATH**
   - Verify installation:**[terraform -version]**
 - Install Terraform on Linux
   - sudo apt update
   - sudo apt install -y gnupg software-properties-common
   - wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
   - echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
   - sudo apt update && sudo apt install terraform
<img alt="Terraform" src="https://www.datocms-assets.com/2885/1731373310-terraform_white.svg" width="600px">
