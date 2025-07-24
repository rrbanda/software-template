# OpenShift Dev Spaces Backstage Software Template Workspace

This repository provides a starter Dev Spaces workspace for building Backstage Software Templates with VS Code and Roo Code AI assistant.

## How to Use

1. **Open in OpenShift Dev Spaces:**
   - Use the `devfile.yaml` to create a new Dev Spaces workspace.
   - This workspace will have VS Code, Roo Code, Node.js, and Git pre-installed.

2. **Workspace Layout**
   - `templates/` - Place each Backstage template in its own subfolder here.
   - `location.yaml` - Register templates here for Backstage.
   - `README.md` - This file.

3. **How to Use Roo Code**
   - Click the Roo Code extension icon in VS Code sidebar or use Command Palette.
   - Example prompt:  
     > "Create a Backstage template.yaml for a Node.js backend service with a customizable service name and GitHub Actions workflow."
   - Roo Code will generate YAML, folder structures, or code as requested.

4. **Typical Project Structure**
---
## Project Structure

```
templates/
└── nodejs-backend/
├── template.yaml
└── skeleton/
├── index.js
├── package.json
└── Dockerfile
location.yaml

```
### 5. **Next Steps**
- Add new templates via Roo Code or manually.
- Commit and push to your GitHub repo.
```

