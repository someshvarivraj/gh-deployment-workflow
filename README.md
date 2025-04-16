# gh-deployment-workflow
Project URL : https://roadmap.sh/projects/github-actions-deployment-workflow
GitHub Actions Deployment Workflow
This project demonstrates a simple Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions to deploy a static website to GitHub Pages.
Project Structure

index.html: The main webpage that gets deployed.
.github/workflows/deploy.yml: The GitHub Actions workflow configuration.
README.md: This file, explaining the project.

How It Works

Any push to the main branch that modifies index.html triggers the GitHub Actions workflow.
The workflow checks out the code, configures GitHub Pages, uploads the site files, and deploys them.
The deployed site is accessible at [https://someshvarivraj.github.io/gh-deployment-workflow/)/](https://someshvarivraj.github.io/gh-deployment-workflow/).

Setup Instructions

Create a GitHub repository named gh-deployment-workflow.
Add the files from this project to the repository.
Enable GitHub Pages in the repository settings:
Go to Settings > Pages.
Set the source to Deploy from a branch.
Select main branch and / (root) folder.


Push changes to the main branch to trigger the deployment.

