# Cloud Dimensions ServiceNow CI/CD Training Lab Template

This repository is the starting point for the ServiceNow CI/CD Fundamentals course labs.

## How to use this template

1. Select **Use this template** at the top of this page.
2. Select **Create a new repository**.
3. On the create screen, select **Include all branches** so your copy includes both lab starting branches.
4. Choose your own GitHub account as the owner and enter a repository name such as `servicenow-cicd-lab`.
5. Select **Create repository**.

You add repository secrets and edit the workflow file in your own copy throughout the course.

## Lab branches

| Branch | Lab | Lesson |
|---|---|---|
| `lab2-start` | Lab 2: Promote an Application Using the CICD API | Lesson 4 |
| `lab3-start` | Lab 3: Build a GitHub Actions Workflow | Lesson 6 |

Each branch contains a `.github/workflows/cicd.yml` file with a starting state that matches the lab instructions. Open the branch on GitHub to see the stub and the `# TODO` comments that mark what you need to add.

## Secrets required

Before running any lab pipeline, add the following repository secrets in **Settings > Secrets and variables > Actions**:

| Secret name | Value |
|---|---|
| `SN_INSTANCE_URL` | Your ServiceNow lab instance URL |
| `SN_CLIENT_ID` | The Client ID from your OAuth Application Registry endpoint |
| `SN_CLIENT_SECRET` | The Client Secret from your OAuth Application Registry endpoint |

See Lab 1 (Lesson 2) for instructions on creating these secrets.

---

*Cloud Dimensions internal training resource. For course support, contact the ServiceNow University team.*
