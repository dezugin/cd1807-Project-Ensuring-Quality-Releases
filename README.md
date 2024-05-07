![status](https://dev.azure.com/udacitydeSouza/udacitydevops/_apis/build/status%2Fdezugin.cd1807-Project-Ensuring-Quality-Releases?branchName=main)

# Ensuring Quality Releases

## Overview
This project focuses on utilizing Infrastructure as Code (IaC) with Terraform, implementing CI/CD pipelines in Azure DevOps, and conducting various automated tests to ensure the quality of software releases. The project is structured to create an effective testing environment that mimics different stages of the release management process.

## Environment Creation and Deployment

### Objectives
- Utilize Terraform to create structured environments for testing.
- Integrate automated testing tasks in CI/CD pipelines using Azure DevOps to reduce the percentage of failed tests.

### Setup Instructions
1. **Terraform Configuration**
   - Configure Terraform to manage infrastructure.
   - Ensure that Terraform files are set up to reflect different environment tiers.
   - Run Terraform with CI/CD pipeline and capture the log output. Make sure to enable timestamp visibility in the pipeline job logs.

   **Submission:**
   - Terraform files for the test environment.
   - Screenshot of the Terraform log output from the CI/CD pipeline.

2. **Azure DevOps Pipeline**
   - Modify the `azure-pipelines.yaml` to include automated testing tasks.
   
   **Submission:**
   - The `azure-pipelines.yaml` file.
   - Screenshot of the successful execution of the pipeline build results page.

## Automated Testing

### Objectives
- Implement load testing for web applications and services using JMeter.
- Execute functional testing using Selenium for web application interactions.
- Conduct API integration tests using Postman for RESTful services.

### Testing Procedures
1. **Load Testing with JMeter**
   - Design and execute a JMeter test suite to assess application performance under stress.

   **Submission:**
   - JMeter test suite and HTML-generated report of test results.
   - Screenshot of JMeter log output from CI/CD pipeline execution.

2. **Functional Testing with Selenium**
   - Create Selenium test cases for user interactions with a web application.

   **Submission:**
   - Python test case files.
   - Screenshot of the Selenium test suite execution in the CI/CD pipeline.

3. **API Testing with Postman**
   - Develop Postman test collections for API integration and validation.

   **Submission:**
   - Postman test collections and screenshots of Test Run Results from Azure DevOps.

## Monitoring & Observability

### Objectives
- Set up Azure Monitor and Azure Log Analytics to monitor and analyze application performance and operational health.

### Configuration Instructions
1. **Azure Monitor**
   - Configure alerts and review the notification system through Azure Monitor.

   **Submission:**
   - Screenshots of the alert notifications, resource graphs, and alert rule configurations.

2. **Azure Log Analytics**
   - Implement queries to monitor and analyze custom application events.

   **Submission:**
   - Screenshots of Log Analytics queries and results.

## Conclusion
This project aims to provide a hands-on approach to learning how to ensure quality software releases through effective environment management, automated testing, and robust monitoring.

## Contributions
Contributions to this project are welcome. Please ensure that any pull requests or changes adhere to the project's standards and specifications.

