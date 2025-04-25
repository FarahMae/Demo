# Demo

📝 GitHub Actions Workflow Report
📌 Project: Demo Repository
File Location: .github/workflows/main.yml
Workflow Name: hello-world

🔍 Objective
To create a basic CI/CD pipeline using GitHub Actions that runs a simple shell command (echo "Hello World") every time code is pushed to the repository. This demonstrates an understanding of workflow automation using GitHub’s CI/CD features.

🛠️ Tools & Technologies Used
GitHub Actions

YAML

Ubuntu (GitHub-hosted runner)

📄 Workflow Configuration (main.yml)
yaml
Copy
Edit
name: hello-world

on: push

jobs:
  my-job:
    runs-on: ubuntu-latest
    steps:
      - name: my step
        run: echo "Hello World"
🧠 Explanation
Trigger: The workflow is triggered on any push event to the repository.

Job: A single job (my-job) runs on the latest Ubuntu runner provided by GitHub.

Step: Executes a simple command echo "Hello World" to validate that the workflow runs successfully.

✅ Output & Result
The workflow completes successfully and prints the message Hello World in the Actions log every time a push is made. This confirms that:

GitHub Actions are configured correctly

The syntax and YAML structure are valid

You understand the basics of GitHub CI/CD pipeline structure

