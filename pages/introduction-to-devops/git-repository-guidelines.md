# Git Repo Guidelines 🌐

The Git Feature Branch Workflow is a powerful approach that aligns with the principles of social coding. It enhances collaboration and code quality within your development team. Here's how it works:

## **Guidelines for Your Repositories and Workflow**

1. **Single Repository for Each Component:** Create a separate repository for each component, whether it's a microservice or another module. Avoid using monorepos (a single repository with multiple microservices). This practice keeps codebases organized and allows team members to focus on what's relevant to them.

2. **Branch for Every Issue:** Avoid long-lived branches. Instead, create a new branch for every issue or feature you're working on. Branches in Git are lightweight, and you should delete them once the work is done. Avoid the old "development" branch approach.

3. **Pull Requests for Code Merging:** Make pull requests your primary method of merging code back into the master branch. Never merge your pull request yourself. This approach encourages code reviews and ensures that at least one other team member reviews your work before it's integrated.

## **The Git Feature Branch Workflow**

Here's a step-by-step breakdown of the Git Feature Branch Workflow:

1. **Create a Repository:** Start by creating a repository for your component on a platform like GitHub. If you're contributing to an existing component, fork the relevant repository.

2. **Clone to Local Repository:** Clone the repository to your local workstation. Your local repository becomes the space where you make changes and create feature branches.

3. **Create a Feature Branch:** For each issue, feature, or bug fix you're working on, create a dedicated feature branch. This branch will contain the code associated with the specific GitHub Issue you're addressing.

4. **Push to a Remote Branch:** Once you've completed your work or want feedback, push the code from your local feature branch to a remote branch on the repository platform. This makes your code accessible to the rest of the team.

5. **Create a Pull Request:** To request code review or integrate your changes, create a pull request. The pull request provides an opportunity for code review and discussion. If your changes meet the team's standards and the code is complete, it will be merged into the master branch and become part of the original repository.

The Git Feature Branch Workflow is highly effective for social coding as it promotes a structured and collaborative development environment. It ensures that code changes are reviewed, and it enables a controlled process for integrating code back into the master branch. By adhering to these practices, your team can benefit from enhanced code quality, efficient collaboration, and more streamlined development processes.
