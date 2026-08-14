

Q. How do you typically manage and secure Terraform remote state in Azure across dev / test / prod (storage, locking and access control)?

Q. How do you prevent two engineers from applying Terraform to the same state at the same time? And what do you do if the state gets locked unexpectedly?

Q. Can you walk me through the specific mechanism you rely on in Azure to handle Terraform state locking and how you’d safely clear a stale lock without risking state corruption? 

Q. If a Terraform state lock becomes stale (for example a CI job crashed), what exact steps do you take to verify it’s safe to unlock and then remove the lock?

Q. In Terraform, what’s the purpose of a plan versus an apply, and when would you require a human approval gate in the CI/CD pipeline?

Q.  How do you typically organize Terraform code for multiple environments (dev / stage / prod) while keeping modules reusable and variables separated?

