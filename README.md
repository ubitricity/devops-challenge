# devops-challenge
Devops challenge

### Given
GCP account information will be shared with the candidate. This account will have permission to a GCP project called recruitment.
First name and Last name of the candidate will be used to create the account e.g.: john.doe@recruitment.ubitricity.com

### Requirement
Create a Virtual Machine using Terraform which can run nginx and support 10000 concurrent https connections.
Run nginx in it enabling SSL and redirecting port 80 to 443 (Use Let's Encrypt or snakeoil certificate)
The VM should be reachable using an URL and SSH.

### Deliverable
1. Github repository link with terraform code for the given requirements.
2. URL for accessing the running nginx VM.
