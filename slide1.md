layout: true
class: compact
background-image: url(../../assets/images/backgrounds/HashiCorp-Content-bkg.png)
background-size: cover
name: slide1

## Introduction to Packer and Terraform

Packer and Terraform are powerful tools developed by HashiCorp for infrastructure automation

Packer is used to create machine images from source configuration 

```bash
curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
sudo apt-get update && sudo apt-get install packer
```
---
Terraform is used to provision and manage infrastructure using those images 
```bash
# Add HashiCorp GPG key
curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -

# Add HashiCorp repository
sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"

# Update package index
sudo apt-get update

# Install Terraform
sudo apt-get install terraform
```
???
Together, they offer a seamless workflow for creating, distributing, and deploying images
???
