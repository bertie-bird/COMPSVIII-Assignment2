What triggers this workflow to run? (Look at the on: section)
  1. Code that's being pushed to the main branch is what triggers the workflow to run or another trigger is when a pull request has been made to the main branch.

What are the four main steps this workflow performs? (List each step name)
  1.Checkout Code
  2.Validate HTML
  3.Check Links
  4.Upload Artifact
  
What does the "Checkout code" step do and why is it necessary?
  1. You get the code from the repository and it necessary because that is the basis for the next three steps.
  
What is the purpose of the environment configuration?
  1. It configures the deployment of the GitHub pages.
  
How does this automated deployment improve reliability compared to manual deployment?
  1. It allows for deployment to occur whenever and not contained within working hours. Automated deployment also allows for a consistent repeatable process and error-free execution.

What would happen if you pushed code to a different branch (not main)?
  1. If code is pushed to a branch that isn't the main the workflow will not run.
