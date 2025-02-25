## **📑 Table of Contents**
1. [Introduction](#1-introduction)
   - [What is a GitHub Project?](#11-what-is-a-github-project)
   - [Benefits](#12-benefits)
   - [Who Should Use GitHub Projects?](#13-who-should-use-github-projects)

2. [Setting Up Your GitHub Project](#2-setting-up-your-github-project)
   - [From the web](#21-from-the-web)
   - [From VS code](#22-from-vs-code)
3. [How GitHub Projects Work](#3-how-github-projects-work)
   - [Milestones](#31-milestones)
   - [Issues & Sub-issues](#32-issues--sub-issues)
   - [Tags (Labels)](#33-tags-labels)
   - [Branches](#34-branches)
   - [Comments](#35-comments)
   - [Assigning People](#36-assigning-people)

4. [Visualizations in GitHub Projects](#4-visualizations-in-github-projects)
   - [Dashboard View](#41-dashboard-view)
   - [Board (Kanban) View](#42-board-kanban-view)
   - [Timeline View](#43-timeline-view)
   - [Automated Views](#44-automated-views)

5. [Automating Your Workflow](#5-automating-your-workflow)
   - [Automation Possibilities](#51-automation-possibilities)
   - [Automation Tools](#52-automation-tools)

6. [Conventional Good Practices](#6-conventional-good-practices)

7. [Deploying Your GitHub Project](#7-deploying-your-github-project)

8. [Managing a GitHub Project](#8-managing-a-github-project)

9. [Linking GitHub Projects to Repositories](#9-linking-github-projects-to-repositories)

10. [Useful Links](#10-useful-links)


### Automation 🤖

1. [Setting Up Automation in GitHub Projects](#setting-up-automation-in-github-projects)
2. [Workflow Creation (Step-by-Step)](#workflow-creation-step-by-step)
   - [a. Create the Directory](#a-create-the-directory)
   - [b. Add a YAML File](#b-add-a-yaml-file)
   - [c. Push the YAML File](#c-push-the-yaml-file)
   - [Example of CI/CD with GitHub Actions](#example-of-cicd-with-github-actions)
3. [Triggers in GitHub Actions](#triggers-in-github-actions)
4. [Where to Place the YAML File](#where-to-place-the-yaml-file)
5. [Automating Tasks in the GitHub Projects Interface](#automating-tasks-in-the-github-projects-interface)
   - [When to Use YAML vs. GitHub UI?](#when-to-use-yaml-vs-github-ui)



---

# **1. Introduction**

## **1.1. What is a GitHub Project?**
A tool for organizing tasks, tracking issues, pull requests, milestones, and more.

## **1.2. Benefits**
- **Task Management:** Track work across stages.  
- **Collaboration:** Work seamlessly with teammates.  
- **Milestone Tracking:** Set goals and deadlines.

## **1.3. Who Should Use GitHub Projects?**
- **Developers:** Manage code changes and tasks.  
- **Project Managers:** Plan and track timelines.  
- **Collaborators:** View status and contribute.

---

# **2. Setting Up Your GitHub Project**

## **2.1 From the Web**
- Go to the repository → Projects tab → New Project.  
- Select a template (Kanban, Basic, Roadmap).

## **2.2 From VS Code**
Why we cannot do this from  VS code ??

- Repository:
A repository (or "repo") is a storage space for your project files and their version history. It can be hosted on platforms like GitHub.
When you create a repository on GitHub, you create a container for your project.
- Project:
A project refers to the actual work you are doing, which includes code, documentation, and other assets.
In GitHub, "project" can also refer to a feature for organizing tasks (like Kanban boards), but this is separate from the repository.
- Linking:
You can use git remote add origin <repository-url> to link your local Git repository to a remote GitHub repository.
You cannot link a "project" directly because Git operates at the repository level. Your local project must first be a Git repository (initialized with git init) before you can link it to a remote repository.

---

# **3. How GitHub Projects Work**

## **3.1. Milestones**
Checkpoints for issue sets (e.g., releases).

## **3.2. Issues & Sub-issues**
Represent tasks or bugs.

## **3.3. Tags (Labels)**
Categorize issues (e.g., bug, feature).

## **3.4. Branches**
Develop features separately and merge into main.

## **3.5. Comments**
Enable discussion and feedback.

## **3.6. Assigning People**
Allocate tasks to team members.

---

# **4. Visualizations in GitHub Projects**

## **4.1. Dashboard View**
Kanban-style, columns like To Do, In Progress, Done.

## **4.2. Board (Kanban) View**
Customizable stages (e.g., Code Review, Testing).

## **4.3. Timeline View**
Calendar view for tasks and milestones.

## **4.4. Automated Views**
Auto-updates based on actions like closing issues.

---

# **5. Automating Your Workflow**

## **5.1. Automation Possibilities**
- Automate issue movement, labeling, assigning, pull requests, and workflows using GitHub Actions.

## **5.2. Automation Tools**
- GitHub Actions https://github.com/features/actions 
- GitHub Apps https://docs.github.com/en/apps 
- Zapier https://zapier.com/apps/github/integrations 
- IFTTT https://ifttt.com/github 
- Automate.io https://automate.io/ 
- Probot https://github.com/probot/probot 
- Dependabot  https://docs.github.com/en/code-security/dependabot/working-with-dependabot/automating-dependabot-with-github-actions 
- Renovate https://github.com/renovatebot/renovate 
- GitHub Projects Automation Rules (UI) https://docs.github.com/en/issues/planning-and-tracking-with-projects/automating-your-project 
- GraphQL https://graphql.org/ 

---

# **6. Conventional Good Practices**
- Write descriptive issues.
- Break down large tasks.
- Use good commit messages.
- Consistent labeling.
- Keep boards clean and updated.

---

# **7. Deploying Your GitHub Project**
- Deployment tools: GitHub Pages, Netlify, Vercel.
- Use GitHub Actions for automated deployment.

---

# **8. Managing a GitHub Project**
- Track progress with task movement and milestones.
- Assign tasks and set deadlines.
- Collaborate through comments and pull requests.

---

# **9. Linking GitHub Projects to Repositories**
- Link projects to repositories for integrated issue and code tracking.

---

# **10. Useful Links**
Here are some useful links to help with project planning, tracking, and commits conventions:

- **About projects (Spanish):** [Learn about GitHub Projects](https://docs.github.com/es/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)
- **Starting a project:** [Quickstart for GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects)
- **Conventional commits:** [Conventional Commits Guide](https://www.conventionalcommits.org/en/v1.0.0/)
- **Planning and follow-up of projects (Spanish):** [Project Planning and Tracking](https://docs.github.com/es/issues/planning-and-tracking-with-projects)
- **Issues functions:** [GitHub Issues Features](https://github.com/features/issues)


# AUTOMATION 🤖

1. [Setting Up Automation in GitHub Projects](#setting-up-automation-in-github-projects)
2. [Workflow Creation (Step-by-Step)](#workflow-creation-step-by-step)
   - [a. Create the Directory](#a-create-the-directory)
   - [b. Add a YAML File](#b-add-a-yaml-file)
   - [c. Push the YAML File](#c-push-the-yaml-file)
   - [Example of CI/CD with GitHub Actions](#example-of-cicd-with-github-actions)
3. [Triggers in GitHub Actions](#triggers-in-github-actions)
4. [Where to Place the YAML File](#where-to-place-the-yaml-file)
5. [Automating Tasks in the GitHub Projects Interface](#automating-tasks-in-the-github-projects-interface)
   - [When to Use YAML vs. GitHub UI?](#when-to-use-yaml-vs-github-ui)

---

## 1. Setting Up Automation in GitHub Projects

## 2. Workflow Creation (Step-by-Step)
A workflow in GitHub Actions is an automated set of tasks that run in response to specific events, such as pushing code to the repository. Here's the process:

### a. Create the Directory
Create a folder named `.github/workflows` within your repository. This is the default location where YAML (Yet Another Markup Language) files for automation should be placed.

### b. Add a YAML File
The YAML file defines triggers and automated tasks (jobs). Here's an example of a simple YAML file:

```yaml
name: Run Tests
on: [push] # Triggered when code is pushed to the repository
jobs:
  test:
    runs-on: ubuntu-latest # The environment to run the job
    steps:
      - name: Checkout code
        uses: actions/checkout@v2 # Downloads the repository code
      - name: Run Tests
        run: npm test # Executes the tests defined in your project
```

- **name:** The name of the workflow.
- **on:** The event that triggers the workflow, in this case, `push` (code push).
- **jobs:** The tasks to execute, here there's only one job named `test`.
- **steps:** The steps of the job, including checking out the code and running tests (`npm test`).

### c. Push the YAML File
Push the file to the repository. Once uploaded, GitHub will start the automation every time the configured trigger is activated (in this example, on every push).

### Example of CI/CD with GitHub Actions
The following example extends automation to implement a CI/CD (Continuous Integration and Continuous Deployment) pipeline:

```yaml
name: CI/CD Pipeline
on:
  push:
    branches:
      - main # Only triggers when code is pushed to the "main" branch
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v2
      - name: Run Tests
        run: npm test
        
  deploy:
    runs-on: ubuntu-latest
    needs: test # This job runs only if the "test" job is successful
    steps:
      - name: Deploy to production
        run: ./deploy_script.sh # Executes a custom deployment script
```

- Two jobs: `test` and `deploy`.
- **needs:** Ensures that `deploy` only runs if `test` completed without errors.
- **deploy_script.sh:** A custom script to deploy your application to production.

---

## 3. Triggers in GitHub Actions
Triggers are events that start a workflow. Common examples include:
- **Push Event:** Triggered when code is pushed to a branch.
- **Pull Request Event:** Triggered when a pull request is created or updated.
- **Scheduled Event:** Automates tasks at a set time (using cron jobs, like every Monday at 9 am).
- **Issue/PR Comment Event:** Triggers when a comment is added to an issue or pull request.

Example YAML for a push event to the `main` branch:

```yaml
on:
  push:
    branches:
      - main
```

---

## 4. Where to Place the YAML File
You must save the YAML file in the following path within your repository:

```plaintext
.github/workflows/
```

If the file is not in this specific location, GitHub will not detect the automation.

---

## 5. Automating Tasks in the GitHub Projects Interface
In addition to YAML files, GitHub Projects offers simpler automation through its interface:
- Automatically moving issues between columns (e.g., from "To Do" to "In Progress").
- Assigning labels or assignees to issues based on conditions.

### To set this up:
1. Go to the **Projects** tab.
2. Select **Automation**.
3. Set the desired rules.

### When to Use YAML vs. GitHub UI?
- **Use the GitHub Projects UI** for simple and visual automations.
- **Use YAML files in `.github/workflows/`** for advanced automations, like continuous integration, automatic deployments, or complex tasks.


