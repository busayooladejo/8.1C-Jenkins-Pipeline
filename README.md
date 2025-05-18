# 8.1C CI/CD Pipeline Demo

This repository is created for the SIT753 Credit Task - Part 1: GitHub Integration and CI/CD Pipeline with Jenkins.

## Project Structure

This project is used to simulate a Jenkins pipeline with the following stages:

1. Build
2. Unit and Integration Tests
3. Code Analysis
4. Security Scan
5. Deploy to Staging
6. Integration Tests on Staging
7. Deploy to Production

## Tools Used

- **Build:** Maven / npm
- **Testing:** JUnit, Mocha
- **Code Analysis:** SonarQube, ESLint
- **Security:** Snyk, npm audit
- **Deployment:** SSH, Docker, AWS CLI

## How to Use

This repo is connected to Jenkins and configured to trigger a new pipeline build automatically using SCM polling every 5 minutes when a new commit is detected.

## Author

**Name:** Busayo Oladejo
** Sudent ID**: 224665671

