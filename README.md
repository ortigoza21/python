# DevSecOps CI/CD Pipeline - IT510 Unit 5

## Overview
This project demonstrates the implementation of a DevSecOps CI/CD pipeline using GitHub Actions. The pipeline automates the process of integrating, building, testing, securing, and deploying application code in a structured and repeatable workflow.

The goal of this project is to apply DevSecOps principles by integrating automation and security into each stage of the software development lifecycle.

---

## Pipeline Workflow

The pipeline follows this sequence:

Developer → GitHub Repository → CI Trigger → Build → Testing → Security → Artifact → Deployment → Monitoring

---

## Technologies Used

- GitHub (Source Control)
- GitHub Actions (CI/CD Automation)
- Python (Application and Testing)
- YAML (Workflow Configuration)

---

## Pipeline Stages

### 1. Source Control
All code is stored and managed in GitHub, allowing version control, collaboration, and traceability of changes.

### 2. Continuous Integration Trigger
The pipeline automatically runs when code is pushed to the repository, ensuring immediate validation of changes.

### 3. Build Stage
The application is compiled and validated to confirm that it runs correctly in a clean environment.

### 4. Automated Testing
Test scripts are executed to ensure that application functionality works as expected and that new changes do not introduce errors.

### 5. Security Scan
A simulated security scan is included to demonstrate DevSecOps practices by identifying potential vulnerabilities early in the pipeline.

### 6. Artifact Management
Application files are packaged and stored as build artifacts to ensure consistency and traceability across environments.

### 7. Continuous Deployment
The pipeline simulates deployment to demonstrate how validated code moves toward a production-ready environment.

### 8. Monitoring and Feedback
Pipeline logs and execution results provide feedback to developers, allowing continuous improvement and quick issue detection.

---

## How to Run the Pipeline

1. Push changes to the repository
2. Navigate to the **Actions** tab in GitHub
3. Select the latest workflow run
4. Review logs for each stage of the pipeline

---

## Project Files

- `app.py` → Main application file  
- `test_app.py` → Automated test script  
- `.github/workflows/ci.yml` → CI/CD pipeline configuration  

---

## Purpose

This project demonstrates how DevSecOps practices can be implemented using automation tools to improve software quality, reduce errors, and ensure secure and efficient deployments.

---

## Author

Carlos Ortigoza  
IT 510 – DevSecOps  
