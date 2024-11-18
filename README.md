# Cloud Resume Challenge - Infrastructure

This repository contains the infrastructure components for the **Cloud Resume Challenge**, managed using Terraform to automate and provision cloud resources.

## Repository Structure

- **`terraform/`**: Directory containing Terraform configuration files.
  - **`.terraform.lock.hcl`**: Lock file for Terraform, which ensures consistent dependency versions.
  - **`main.tf`**: The primary Terraform configuration file, defining the cloud infrastructure resources.

## Setup and Deployment

1. **Install Terraform**:
   - Make sure Terraform is installed on your machine. You can download it from [Terraform's official website](https://www.terraform.io/downloads.html).

2. **Initialize Terraform**:
   Navigate to the `terraform/` directory and initialize Terraform to download necessary providers and modules:
  ```terraform init```
   
3. **Plan Infrastructure**:
Review the changes that Terraform will make to your cloud environment:
 ```terraform plan```


4. **Apply Infrastructure**:
Deploy the resources defined in `main.tf` to your cloud provider:
  ```terraform apply```

5. **Verify Deployment**:  
   After applying the configuration, verify that all necessary cloud resources are up and running.  
   Ensure that the infrastructure is correctly configured to support the backend and frontend components of the Cloud Resume Challenge.

## Project Details

This infrastructure setup provisions the cloud resources necessary for the backend and frontend components of the Cloud Resume Challenge. Using Terraform allows for easy, repeatable deployments and consistent cloud resource management.

