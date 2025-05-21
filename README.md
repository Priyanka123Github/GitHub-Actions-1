# GitHub-Actions-1

GitHub Actions
feature in GitHub to create custom automated Workflows
automate SDLC workflows
implement CI CD DevOps
run a task on a specific event

 DEMO
 Step 1 - Sign up or Login to GitHub.com 
 Step 2 - Create a new repository
 Step 3 - In the repo create a folder .github/workflows
 Step 4 - In the folder create a YAML file with extension .yml
 Step 5 - Add the workflow content to the file
 Step 6 - Commit and push the changes
 Step 7 - Goto main page of the repo and goto “Actions”
 Step 8 - Select the workflow from the left side and check the logs and results

 Terms:
 WORKFLOW : collection of jobs, defined in a YAML file
 name:
 EVENTS : any activity in the repo that can trigger a workflow 
 on:
 JOBS : collection of steps
 jobs:
 STEPS : actions to be taken, commands, scripts
 steps:
 Chain Jobs - :needs
