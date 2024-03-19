# Azure Virtual Machine Deployment with Terraform

This Terraform configuration enables the deployment of a virtual machine (VM) on Microsoft Azure, along with necessary network configurations and security settings.

## Prerequisites

Before getting started, make sure you have the following installed on your local machine:

- [Terraform](https://www.terraform.io/downloads.html)
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)

## **_Build With_** 

<div style="text-align: left">
    <p>
        <a href="https://code.visualstudio.com" target="_blank"> <img alt="V" src="https://raw.githubusercontent.com/devicons/devicon/55609aa5bd817ff167afce0d965585c92040787a/icons/vscode/vscode-original.svg" height="60" width = "60"></a>
        <a href="https://www.terraform.io/" target="blank"><img src="https://static-00.iconduck.com/assets.00/terraform-icon-1803x2048-hodrzd3t.png" width="60" alt="Terraform Logo" /></a>
        <a href="https://https://portal.azure.com/#home/" target="blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Microsoft_Azure.svg/1200px-Microsoft_Azure.svg.png" width="60" alt="Azure Logo" />
   
    
</div>


## Usage

1. Clone this repository to your local machine.
2. Navigate to the directory containing the Terraform files.
3. Modify the `terraform.tfvars` file to customize variables like `name`, `location`, and `username`.
4. Initialize Terraform by running `terraform init`.
5. Preview the changes Terraform will make by running `terraform plan`.
6. Apply the changes by running `terraform apply`.
7. Confirm the changes when prompted.
8. Once deployment is complete, access the deployed resources via Azure Portal or command line.

## Structure

The Terraform configuration is organized as follows:

- `main.tf`: Contains the main configuration for creating Azure resources like resource group, virtual network, subnet, and VM module.
- `variables.tfvars`: Defines input variables like `name`, `location`, and `username`.
- `outputs.tf`: Defines output values, such as the public IP address of the VM.
- `/modules/vm/main.tf`: Contains configurations specific to the VM module, including network interface, SSH key pair, and network security group.

## **_Authors_** ✒️

<div style="text-align: left">
    <a href="https://github.com/G20-00" target="_blank"> <img alt="G20-00" src="https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/70019070?v=4&h=60&w=60&fit=cover&mask=circle"></a>
</div>
---

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/for-you.svg)](https://forthebadge.com)
