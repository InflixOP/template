# 🚀 Project Template Repository

> A GitHub repository template with essential GitHub templates pre-configured for consistent project setup.

## 📋 What's Included

This template provides:

### 🗂️ Repository Structure
```
├── README.md                          # Project documentation
├── LICENSE                            # MIT License
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md             # Bug report template
    │   └── feature_request.md        # Feature request template
    └── PULL_REQUEST_TEMPLATE.md      # PR template
```

### 🛠️ Pre-configured Features

- **Issue Templates**: Standardized bug reports and feature requests
- **Pull Request Template**: Consistent PR structure and checklist
- **License**: MIT License (easily replaceable)

## 🚀 How to Use This Template

### Option 1: Using GitHub Web Interface
1. Click the **"Use this template"** button above
2. Choose **"Create a new repository"**
3. Fill in your repository details:
   - Repository name
   - Description
   - Public/Private visibility
4. Click **"Create repository from template"**

### Option 2: Using GitHub CLI
```bash
gh repo create your-project-name --template your-username/project-template --public
cd your-project-name
```

### Option 3: Using GitHub API
```bash
curl -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer YOUR_TOKEN" \
  https://api.github.com/repos/your-username/project-template/generate \
  -d '{
    "owner": "your-username",
    "name": "your-new-project",
    "description": "Description of your new project",
    "private": false
  }'
```

## 📄 License

This template is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
