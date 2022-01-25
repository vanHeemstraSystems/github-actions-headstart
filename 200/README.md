# 200 - Course

Based on "hello-github-actions" at https://github.com/willem-vanheemstrasystems/hello-github-actions/issues/1

# Welcome

This course helps you create a simple GitHub Action and use that action in a workflow. 

## What are GitHub Actions?

GitHub Actions are a flexible way to automate nearly every aspect of your team's software workflow. Here are just a few of the ways teams are using GitHub Actions:

- Automated testing (CI)
- Continuous delivery and deployment
- Responding to workflow triggers using issues, @ mentions, labels, and more
- Triggering code reviews
- Managing branches
- Triaging issues and pull requests

The sky is truly the limit with GitHub Actions.

The best part, these workflows are stored as code in your repository and easily shared and reused across teams.

To learn even more, check out the [GitHub Actions feature page](https://github.com/features/actions), or the [GitHub Actions documentation](https://help.github.com/en/actions).

### Before you begin

In this course you will work with issues and pull requests, as well as edit files. If these things are not familiar to you, we recommend you take the [Introduction to GitHub](https://lab.github.com/githubtraining/introduction-to-github) course, first!

### Actions and Workflows

There are two components to using GitHub Actions that we'll cover:

- the **action** itself
- a **workflow** that uses action(s)

A workflow can contain many actions. Each action has its own purpose. We'll put the files relating to the action in their own directories.

### Types of Actions

Actions come in two types: **container actions** and **JavaScript actions**.

Docker **container actions** allow the environment to be packaged with the GitHub Actions code and can only execute in the GitHub-Hosted Linux environment.

**JavaScript actions** decouple the GitHub Actions code from the environment allowing faster execution but accepting greater dependency management responsibility.

<!--
UNCOMMENT WHEN THESE TWO COURSE GO LIVE AND ADD PROPER LINK DETAILS
📖 To learn more about creating each type of action, refer to the related learning lab course:
  - [Writing JavaScript Actions]()
  - [Writing Docker Container Actions]() -->

## 100 - Add a Dockerfile

See [README.md](./100/README.md)

## 200 - Add an entrypoint script

See [README.md](./200/README.md)

## 300 - Add an action.yml file

See [README.md](./300/README.md)

## 400 - Start your workflow file

See [README.md](./400/README.md)

## 500 - Run an action from your workflow file

See [README.md](./500/README.md)

## 600 - Trigger the workflow

See [README.md](./600/README.md)

## 700 - Incorporate the workflow

See [README.md](./600/README.md)
