# Terraform Questions at Cognizant

Q . Have you worked with Terraform Modules?

Q . Rate yourself on Terraform.

Q . What is the difference between the Terraform block (required_providers) and the Provider block?

Q . What is the difference between AzureRM Provider and AzAPI Provider?

Q . When should you use the AzAPI Provider?

Q . Explain the Terraform Import process.

Q . Which files are required while importing existing resources into Terraform?

Q . How would you migrate manually created Azure resources into Terraform?

Q . How do multiple Terraform modules communicate with each other using outputs, variables, and 
dependencies?

Q . Have you created custom Terraform modules or built infrastructure from scratch?

Q . How do you design reusable Terraform modules for multiple environments (Dev, UAT, Prod), and how 
can a single module be reused across all environments?

Q . What are Terraform Workspaces, why are they used, what are their benefits, and when would you use 
them instead of separate environment folders?

Q . How would you plan and execute a Terraform version upgrade (e.g., from 0.x to 1.x), and what 
compatibility checks would you perform before upgrading?

Q . What is the purpose of null_resource in Terraform, and can you give a practical use case?

Q . What is a Terraform data block, and how do you use it to reference existing Azure resources in your 
code?

Q . If one VM becomes corrupted after deployment, how would you redeploy only that VM using 
Terraform?

Q . If the Terraform state file gets corrupted, how would you recover it, and what are the best practices to 
protect the state file?

Q . How do you securely manage sensitive information such as passwords, keys, and certificates in 
Terraform, and how do you integrate Azure Key Vault?

Q . How would you import existing Azure resources into Terraform so they can be managed as 
Infrastructure as Code?

Q . Have you worked with Azure Verified Modules (AVM) or Cloud Adoption Framework (CAF) Terraform 
modules?

Q . How do you structure your Terraform projects using root and child modules, and do you build your 
own modules or reuse existing ones?

Q . How would you structure your Terraform code using root modules, child modules, locals.tf, for_each, 
and tfvars to follow the DRY (Don't Repeat Yourself) principle, so that common resources (Key Vault, 
Recovery Services Vault, Resource Group, etc.) don't need to be defined for every VM?

Q . Which Terraform meta-arguments support key-value pairs, and when would you use for_each, count, 
map, or nested maps?

Q . If you need temporary access to a Storage Account owned by another team, but they cannot grant you 
RBAC permissions, how would you securely access the Storage Account? Explain the use of SAS Tokens 
and when you would choose them over RBAC.

Q . Suppose a resource was created manually in Azure. How will you manage it using Terraform?
Q . What is Terraform Drift, and how do you detect and safely handle manual changes made through the 
Azure Portal before running terraform plan and terraform apply?

Q . Suppose an application team requests a new VM. What would be your end-to-end approach for 
provisioning the VM using reusable Terraform modules and handing it over to the application team?

Q . Have you worked with Azure Private Endpoints? Suppose a VM suddenly loses connectivity to a 
Storage Account over a Private Endpoint after a Terraform or network change. How would you 

troubleshoot the issue, including verifying Private DNS Zone resolution, NSGs, UDRs, firewall rules, 
port 443, and other network configurations?

Q . How do you design reusable Terraform modules for multiple environments (Dev, UAT, Prod)?

Q . What are Terraform Workspaces, why used, benefits, when instead of separate environment folders?

Q . How would you plan and execute a Terraform version upgrade (e.g., 0.x to 1.x), compatibility checks?

Q . What is the purpose of null_resource in Terraform, practical use case?
Q . What is a Terraform data block, how do you use it to reference existing Azure resources?

Q . If the Terraform state file gets corrupted, how would you recover it, best practices to protect state 
file?

Q . How do you securely manage sensitive information (passwords, keys, certs) in Terraform, integrate 
Azure Key Vault?

Q . How would you import existing Azure resources into Terraform?

Q . What is Terraform Drift, how detect and safely handle manual changes made through Azure Portal 
before plan/apply?

Q . How do you structure Terraform projects using root and child modules, build own or reuse existing?

Q . Application team requests a new VM - end-to-end approach for provisioning using reusable Terraform 
modules and handing it over.

Q . How structure Terraform code using root modules, child modules, locals.tf, for_each, tfvars to follow 
DRY principle?

Q . Which Terraform meta-arguments support key-value pairs - for_each, count, map, nested maps?

Q . VM suddenly loses connectivity to Storage Account over Private Endpoint after Terraform/network 
change - troubleshoot Private DNS Zone, NSGs, UDRs, firewall rules, port 443
