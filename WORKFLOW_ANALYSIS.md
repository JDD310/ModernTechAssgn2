- What triggers this workflow to run? (Look at the on: section)

Code being pushed to the main branch.

-What are the four main steps this workflow performs? (List each step name)

1. Checkout Code
2. Validate HTML
3. Check Links
4. Upload Artifact

- What does the "Checkout code" step do and why is it necessary?

This step gets the code from the repository so that the tests can be preformed on it.

- What is the purpose of the environment configuration?

So that the deployment is ran in the same environment each time.

- How does this automated deployment improve reliability compared to manual deployment?

It eliminates possibility for human error and streamlines the process, making it much faster. 

- What would happen if you pushed code to a different branch (not main)?

This process would not run, because it is set up to only run when code is pushed to main.