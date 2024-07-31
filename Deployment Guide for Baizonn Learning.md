Deployment Guide for Baizonn Learning Centre OpenHouse Website
This guide outlines the development, testing, and deployment workflow for the Baizonn Learning Centre OpenHouse website. 

Communication Channels
Discord: Primary channel for project discussions, updates, and announcements.
WhatsApp: For quick questions and less formal communication.


Project Management
Trello: We use Trello to manage tasks, track progress, and organize project milestones.
Regular Meetings: Schedule weekly meetings to discuss progress, roadblocks, and plan next steps.


Version Control
Git: We use Git for version control to track code changes, collaborate effectively, and maintain a history of the project.
Repository: The main repository is hosted on (https://github.com/orgs/cp3402-students/teams/cp-3402-cms-group-e/repositories).

Development Workflow
Create a Branch: Before starting any new feature or update, create a new branch from the main branch. (e.g., git checkout -b feature/new-homepage)

Local Development:
Theme Development: Customize the HTML, CSS, and potentially JavaScript files within the WordPress theme directory.

WordPress Customizations: Use the WordPress Customizer or create custom page templates as needed.

Test Locally: Preview changes in your local WordPress development environment.

Push Changes: Commit your changes to the branch and push them to the remote repository. (e.g., git push origin feature/new-homepage)

Create a Pull Request: Submit a pull request (PR) on https://github.com/orgs/cp3402-students/teams/cp-3402-cms-group-e/repositories for code review and feedback from the team.

Code Review: Team members review the code, suggest improvements, and discuss changes.

Merge to Main: After approval, merge the branch into the main branch.

Staging Environment
Purpose: The staging environment is a replica of the live website for testing new features and updates before deploying them to production.

Deployment:
Manually pull the latest changes from the main branch to the staging environment.
Alternatively, set up a continuous integration/continuous deployment (CI/CD) pipeline to automate this process.
Testing: Thoroughly test all new features and changes on the staging site.

Production Environment
Deployment: Once changes are fully tested on staging, deploy them to the live (production) website.

Methods:
Manual Deployment: Manually pull the latest changes from the main branch to the production environment.
CI/CD Pipeline: Use a CI/CD tool (like GitHub Actions) to automate the deployment process for faster and more reliable releases.

Testing and Automation
Manual Testing: Perform manual testing on local, staging, and production environments to ensure everything functions as expected.
Automated Testing: (Optional) Implement automated tests for critical functionalities to save time and catch potential issues early.

