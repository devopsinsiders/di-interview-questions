



Q. Terraform code for different environments in single modular approach.

Q. Can you explain about Terraform reusable modules? How do you structure them (root module, child modules, etc.)?

Q. Where do you store the Terraform state file and why?

Q. Why do we use remote backend for state file? What are the benefits?

Q. What is the difference between count and for_each in Terraform? When do you prefer for_each?

Q. How do you destroy a specific resource using Terraform?

Q. What is the Terraform lifecycle / workflow (init, validate, plan, apply)?

Q. Have you worked with manually created resources? How do you bring them under Terraform management?

Q. What is Terraform import and how do you use it?

Q. What kind of errors have you faced during Terraform plan/apply? How do you troubleshoot them?

Q. How do you configure the Terraform provider for Azure? How do you handle multiple subscriptions?

Q. Can we store Terraform state file in Key Vault?

Q. What happens if the Terraform state file gets deleted? How do you recover it?

Q. Which Terraform-related tools have you used for code quality (TFLint, Checkov, etc.)?

Q. How do you manage different environments (Dev, QA, Prod) in Terraform?

Q1. You mentioned you are creating infrastructure as well with your Azure DevOps pipelines. So, you are managing the Terraform part as well?

Q2. You mentioned that you have got exposure with Terraform, right?

Q3. So you have created modules as well with Terraform?

Q4. Have you created some custom modules as well or are you just referencing the official registry for your modules?

Q5. So you are referencing the registry, right? Basically then the Terraform developers, you are just taking their code and you are deploying it and you are using that, right?

Q6. Are there any other changes you are making for your use case?

Q7. Let's say you are using the registry, right?

Q8. There are some versions as well of those modules in the registry, right? Let's say your registry deployed a new official version, a major version of that module. Then how do you make changes in your existing modules after that?

Q9. Let's say you are using a virtual machine module, version 1.2.3, and then the official registry has developed a new version, let's say 3.something, two major versions above your current version. How do you do a version upgrade of your module, on the minor side or on the major side? How do you manage this?

Q10. There might be some issues coming, right? How do you troubleshoot the issues or how do you make sure that you are doing it safely? Let's consider this as a production environment. How do you do the version update safely?

Q11. That will be very time-consuming, right? If I'm just doing it one by one with a patch, there are multiple patch versions that can come with registry. That will be very time-consuming, right? Do you know any optimal strategy to take care here?

Q12. Let's consider you are using your secret information, let's say your database password, API certificates, in your Terraform. I want to make sure that they are never encoded in your Terraform logs as well as in your states. How do you take care of that?

Q13. If let's say in case you are using all these information within your module, let's say there's a database module, so in there you will need the database credentials. Without that, you won't be able to communicate. So how do you make sure that at that point of time when you are passing these secrets, they are not getting exposed in your Terraform logs as well as in your state? How do you manage that?

Q14. How do you fetch it within Terraform?

Q15. But in Terraform, if you are creating Key Vault resource or Key Vault credential, that also you must be creating or deploying within Terraform, right? Or you are doing it manually?

Q16. Then how do you make sure that with Terraform when you are creating this resource, this is not getting exposed in your state? Because if I use it as a resource, my Key Vault resources might still be exposed in my Terraform state. How do you prevent that from happening?

Q17. Now let's say you are using or deploying some critical resources with your Terraform, like your virtual network, machines, databases. I want to make sure that even by accident these resources should not be getting deleted with Terraform. So how do you manage it?

Q18. Are you aware of what lifecycle block you can apply here?

Q19. Now what about multiple environments? How do you manage multiple environments with Terraform?

Q20. So directory structure, are you using separate folders according to the environment, something like that?

Q21. There might be some issues in this Terraform code. You need to fix that and update in the code.

Q22. Please go through it. Try to identify the issue there.

Q23. Whatever you feel like is wrong with the code, you can update it in the code.

Q24. In the subnet variable, there should be three parameters in the cidrsubnet when you are getting the address, or you need to put two parameters?

Q25. The address prefix is there, right? Here it should be three parameters, right? Your CIDR, your number of subnets, and then your count of the index, right?

Q26. You have to do two attributes here. That will not work properly.

Q27. The address prefix that we are using here, we need to have three attributes. Then only it will work.