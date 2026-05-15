# .NET 10 Hello World - DevSecOps Pipeline Example

This repository contains a minimal .NET 10 application prepared to validate:
- CI/CD pipelines
- Azure DevOps reusable templates
- DevSecOps security stages
- Docker image build and scan
- Terraform validation flow
- Environment promotion strategy

## Azure DevOps Templates

Reusable templates are stored in:

```text
azure-devops/templates/
```

Included templates:
- build-api.yml
- security-scan.yml
- docker-build.yml
- deploy.yml
- terraform-security.yml

## Pipeline Flow

Based on the architecture:
- PR validation
- SAST
- SCA
- Secret scanning
- Docker build
- Image scanning
- Terraform security validation
- Multi-environment deployment
