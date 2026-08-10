# 🤝 Contributing Guidelines

First off, thank you for considering contributing to this repository! It's people like you that make this a great resource for everyone preparing for DevOps and DevSecOps interviews.

## 📌 How to Add a New Question

You can add a question either under a specific **Company** or a specific **Topic**. If you know the company that asked the question, please add it under both!

### 1. Adding to a Company Directory
1. **Check if the company exists**: Go to the `companies/` folder. If the company (e.g., TCS, Infosys, Wipro, Tech Mahindra) is not listed, create a new folder for it.
2. **Check if the file exists**: Inside the company folder, look for a markdown file matching the role or primary domain (e.g., `DevOps.md`, `DevSecOps.md`). If it doesn't exist, create it.
3. **Format your question**:
```markdown
### [Role Name / Experience Level] - [Date/Year]

**Technologies:** [e.g., Terraform, Azure, GitHub Actions, tfsec]
**Round:** [e.g., Technical L1, Technical L2, Managerial]
**Question:** 
[Describe the question clearly. e.g., "How do you scan a Terraform repository for security vulnerabilities in an Azure DevOps pipeline?"]

**Thoughts/Hints (Optional):** 
[Any tips on how to approach the problem, mentioning tools like tfsec or checkov]
```

### 2. Adding to a Topic Directory
If the question is heavily focused on a specific technology (like Kubernetes or Terraform), add it to the corresponding file in the `topics/` directory. Use a clear bulleted list format.

## ⚖️ Important Note on NDAs

Please **DO NOT** post any questions that violate a Non-Disclosure Agreement (NDA). Share general concepts, troubleshooting scenarios, and architecture topics rather than verbatim proprietary infrastructure details if you signed an NDA. 

## 🔄 Pull Request Process

1. Ensure your markdown is well-formatted.
2. Submit your PR with a clear title and description.
