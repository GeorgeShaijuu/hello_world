# hello_world

## GitHub Actions Workflow: Hello World

This repository contains a simple GitHub Actions workflow located in `.github/workflows/hello-world.yml`. 

### What the workflow does:

The workflow is triggered automatically whenever code is pushed to the `main` branch.

It defines a single job named `greet` that runs on the latest Ubuntu environment (`ubuntu-latest`) and executes the following steps sequentially:

1. **Say Hello**: Runs the `echo` command to print "Hello, World!" to the console logs.
2. **Show Date**: Runs the `date` command to print the current date and time.
3. **Show System Info**: Runs the `uname -a` command to print detailed system information about the Ubuntu runner.

You can view the execution of these steps by navigating to the **Actions** tab in this GitHub repository after pushing new commits to `main`.