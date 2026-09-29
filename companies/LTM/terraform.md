

Q 1. How did you use TFSec, TFLint and Checkov in your pipeline?

Q 2. How did you lock the Terraform remote state for concurrent PRs?

Q1. What would you do if the Terraform state file is accidentally deleted from the cloud backend?

Q2. If the Terraform state file is recovered and we run terraform apply, but the deployment fails midway, what will happen? How would you handle the situation?

Q3. What happens if we make a change to an NSG that is already managed by Terraform? How would Terraform handle that change?

Q4. If multiple Terraform pipelines are running in parallel and they try to modify the same infrastructure or state file, can they cause conflicts? How would you prevent or handle those conflicts?