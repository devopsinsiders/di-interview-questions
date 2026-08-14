Interview Gold Answer ⭐

Q 1. What is the difference between terraform plan and terraform plan -refresh-only?

A.
terraform plan compares configuration + state + real infrastructure and shows actions required to reach desired state.
terraform plan -refresh-only only checks actual infrastructure against state and reports drift.
terraform apply -refresh-only updates the state file to match the real infrastructure without making any infrastructure changes.

1. Created RGs using Terraform.
2. Deleted RGs manually using Azure CLI.
3. terraform plan → showed 3 resources to create.
4. terraform plan -refresh-only → detected drift.
5. terraform apply -refresh-only → updated state without recreating resources.

terraform plan -refresh-only

State file update nahi karta.

Ye sirf:

Azure se actual infrastructure read karta hai.
State se compare karta hai.
Drift show karta hai.
Execution plan generate karta hai.

Lekin terraform.tfstate ko modify nahi karta.



Q 2. How do you detect Terraform drift?

Answer:

1. terraform plan
   - Shows resources that need to be recreated or modified.
   - Indicates drift indirectly.

2. terraform plan -refresh-only
   - Explicitly detects drift.
   - Shows out-of-band changes.

3. terraform apply -refresh-only
   - Updates state to match actual infrastructure.
   - Does not modify infrastructure.

   terraform plan
= Drift indirectly show kar sakta hai

terraform plan -refresh-only
= Drift explicitly show karta hai

terraform apply -refresh-only
= Drift detect + state update karta hai