# Crédit d'Impôt Innovation (CII) 

## Project Name: Starfix

## Date: 2025-02-05

## Engineer Name: Axel THEVENOT

## Role: Engineer

---

## Task Summary

| **Task Name**        | [Insert Task Name]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Date Started**     | 2025-02-04                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Date Completed**   | 2025-02-21                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Time Spent**       | 14                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Task Description** | Establishing a secure and scalable workflow for integrating Dataform (a data pipeline tool in Google Cloud Platform) with GitHub for the Trooper project.Key challenges included configuring secure authentication via GitHub Personal Access Tokens (PAT), ensuring proper IAM role assignments for the Dataform service account, and enforcing collaboration protocols (e.g., branch protection and pull request requirements). This setup directly contributes to the project’s innovation by enabling automated CI/CD pipelines for data transformations while adhering to security best practices. |

## Details of Innovation Activity

- **Activity Type**:(Select the type of activity associated with the task. Check one or more as applicable.)

  - [ ] Prototyping
  - [ ] Conception
  - [X] Development
  - [ ] Testing
  - [X] Technical Coordination
- **Innovation Objective**:To create a reproducible and secure integration framework between Dataform and GitHub to run the flow, enabling automated data pipeline versioning, collaborative development, and controlled deployments. Innovations include the use of Google Cloud Secrets for PAT storage and granular IAM permissions to minimize security risks.
- **Challenges Faced**:Generating and securely storing GitHub PATs without exposing credentials.IAM Configuration Complexity: Granting the Dataform service account access to secrets while adhering to the principle of least privilege.
  Collaboration Protocol Enforcement: Restricting direct pushes to the main branch to prevent disruptions, requiring pull requests for code reviews.
- **Outcome / Deliverable**:
  Fully connected Dataform repository synced with GitHub.
  Secure storage of PATs in Google Cloud Secrets.
  Configured IAM roles for service accounts
  Established development workflow with branch protection and CI/CD integration.

---

## Supporting Documents / Evidence

- **Attached Files**:
  - [X] Time logs (14)
  - [X] Screenshots of Dataform-GitHub integration steps, repository structure.
  - [X] Setup guide for Dataform-GitHub connectivity, IAM role specifications.
  - [X] Successful pull request merges and automated pipeline executions.

---

## Sign-Off

- **Engineer Signature**: ___________________________________________
- **Date**: _______________

---

## Manager Review Section

### Review by: [Insert Manager’s Name]

- **Task Eligibility for CII**:(Check the eligibility of the task for Crédit d’Impôt Innovation)

  - [X] Eligible for CII
  - [ ] Not Eligible for CII
- **Comments**:[Provide any comments regarding the task, its eligibility, or suggestions for improvement in documenting the activities.]
- **Manager Signature**: ____________________________________________
- **Date**: _______________
