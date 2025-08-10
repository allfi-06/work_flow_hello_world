# work_flow_hello_world
This repository demonstrates the use of GitHub Actions to automate workflow and commit verifications.

The featured workflow, named print-name, is triggered on every push to the main branch and prints the GitHub username of the committer in the Actions log.

## Features
- **GitHub Action Workflow:**
    Includes print-name, located at .git/workflow/print-name.yaml
- **Commit Verification:**
    Contains a specific commit with the message: "Added print-name" on the main branch.
- **Automated Execution:**
    The workflow runs automatically and successfully after each commit to the main branch.
## Usage
#### 1. Clone the repository:
``` 
      git clone https://github.com/allfi-06/work_flow_hello_world.git

      cd work_flow_hello_world      
```
#### 2. Workflow Execution:
  - Push any commit to the main branch.
  - The **print-name** workflow will run and display the GitHub username in the Action log.

## Workflow Details
- **Location:** .github/workflows/print-name.yml
- **Trigger:** On push to main
- **Job:** Prints the GitHub username that made the commit
- **Sample Output:**
`GitHub username: allfi-06'

## Assignment Reference
This repository was created for an assignment involving:
- Updating GitHub credentials and commit verification
- Defining and validating a custom GitHub Actions workflow
- Confirming successful workflow execution in response to repository activity

## Author
Maintained by allfi-06
For professional demonstration and educational purposes.

## Workflow Status

![Workflow Status](https://github.com/allfi-06/work_flow_hello_world/actions/workflows/print-name.yml/badge.svg)
      
