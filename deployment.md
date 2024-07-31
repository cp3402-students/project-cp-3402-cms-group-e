Baizonn Learning Centre OpenHouse Website Deployment 
This document provides a comprehensive workflow for the development, testing, and deployment of the Baizonn Learning Centre OpenHouse website.

Communication Channels
Discord: Primary channel for project discussions, updates, and announcements.
WhatsApp: For quick questions and informal communication.

Project Management
Trello: Utilized for task management, progress tracking, and milestone organization.
Regular Meetings: Weekly meetings are scheduled to discuss progress, address roadblocks, and plan upcoming steps.

Version Control
Git: Employed for version control to track code changes, facilitate collaboration, and maintain project history.
Repository: The main repository is hosted on GitHub.

Development Workflow
Create a Branch:
Before starting any new feature or update, create a new branch from the main branch.
Example: git checkout -b feature/new-homepage

Local Development:

Theme Development: Customize the HTML, CSS, and potentially JavaScript files within the WordPress theme directory.
WordPress Customizations: Use the WordPress Customizer or create custom page templates as needed.
Test Locally: Preview changes in your local WordPress development environment.
Push Changes: Commit your changes to the branch and push them to the remote repository.
Example: git push origin feature/new-homepage
Create a Pull Request: Submit a pull request (PR) on GitHub for code review and feedback from the team.
Code Review: Team members review the code, suggest improvements, and discuss changes.
Merge to Main: After approval, merge the branch into the main branch.
Staging Environment
Purpose: The staging environment replicates the live website, allowing for testing new features and updates before deploying them to production.

Deployment:

Manually pull the latest changes from the main branch to the staging environment.
Alternatively, set up a continuous integration/continuous deployment (CI/CD) pipeline to automate this process.
Testing: Thoroughly test all new features and changes on the staging site.

Production Environment
Deployment: Once changes are fully tested on staging, deploy them to the live (production) website.

Methods:

Manual Deployment: Manually pull the latest changes from the main branch to the production environment.
CI/CD Pipeline: Utilize a CI/CD tool (such as GitHub Actions) to automate the deployment process for faster and more reliable releases.
Testing and Automation
Manual Testing: Conduct manual testing on local, staging, and production environments to ensure all functionalities operate as expected.
Automated Testing: (Optional) Implement automated tests for critical functionalities to save time and identify potential issues early.
