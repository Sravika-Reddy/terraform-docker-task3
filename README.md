\# Task 3: Infrastructure as Code with Terraform



\## Objective

Provision and manage a local Docker container using Terraform.



\## Tools Used

\- Terraform

\- Docker Desktop

\- Git

\- NGINX Alpine image



\## Implementation

1\. Configured the Docker provider in `main.tf`.

2\. Initialized Terraform using `terraform init`.

3\. Validated the configuration using `terraform validate`.

4\. Reviewed the proposed infrastructure using `terraform plan`.

5\. Created an NGINX Docker container using `terraform apply`.

6\. Verified the application by accessing `http://localhost:8085`.

7\. Inspected Docker containers and Terraform state.

8\. Removed the managed infrastructure using `terraform destroy`.



\## Result

The NGINX welcome page was displayed successfully, confirming that the container was running and accessible. The Terraform-managed infrastructure was subsequently destroyed.



\## Execution Evidence

Execution logs and screenshots are included in this repository where available.

