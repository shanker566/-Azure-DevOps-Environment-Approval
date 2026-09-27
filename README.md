# Azure DevOps Pipeline with Environment Approvals

## Introduction

This project demonstrates a CI/CD pipeline using Azure DevOps.
The application is automatically built and deployed through Development,
Testing, and Production environments.

Production deployment requires manual approval to ensure secure and
controlled releases.

## Project Objectives

- Create a Git repository for the application
- Build an automated CI/CD pipeline
- Deploy the application to Development
- Deploy and validate the application in Testing
- Configure Production deployment
- Add manual approval before Production deployment
- Implement secure deployment practices

## Pipeline Flow

Git Repository
      ↓
Build / CI
      ↓
Development
      ↓
Testing
      ↓
Production Approval
      ↓
Production

## Technologies Used

- Microsoft Azure
- Azure DevOps
- Git
- YAML Pipelines
- CI/CD
- Environment Approvals

## Build and Test

The Azure DevOps pipeline automatically builds the application
and performs the required validation before deployment.

## Deployment Environments

### Development
Used for initial application deployment.

### Testing
Used to validate the application before production.

### Production
Final deployment environment. Deployment requires manual approval.

## Security

Production deployment is protected using Azure DevOps environment
approval checks and appropriate permissions.

## Author

B.Tech AI & Data Science