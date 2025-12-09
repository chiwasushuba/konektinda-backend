# CI/CD Sample Project (Node.js)

This repository contains a simple Node.js project with a GitHub Actions CI/CD workflow.

## Workflow Steps

The GitHub Actions pipeline does the following:

1. **Install dependencies** using `npm install`
2. **Run tests** (sample echo test)
3. **Mock deploy** step using `echo "Deploying..."`

## Files

- `.github/workflows/ci.yml` – main GitHub Actions pipeline
- `package.json` – includes a dummy test script

## How to Use

1. Clone the repository
2. Run `npm install`
3. Modify code as needed
4. Push to `main` to trigger the CI/CD workflow

GitHub Actions will run automatically for every push and pull request.
