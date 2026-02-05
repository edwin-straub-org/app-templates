# Basic Application Template

A simple Go HTTP server template.

## Local Development

```bash
go run main.go
```

## Deployment

Push to your repository and the CI/CD pipeline will:
1. Build Docker image
2. Push to container registry
3. Generate application claim
4. Deploy to dev and test stages automatically
