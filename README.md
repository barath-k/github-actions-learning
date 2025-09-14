# GitHub Actions Learning Repository

A repository for learning GitHub Actions workflow setup and CI/CD concepts.

## 🚀 What's Included

This repository contains a simple GitHub Actions workflow that demonstrates:

- Basic workflow structure and syntax
- Trigger events (push, pull request, manual dispatch)
- Job execution on Ubuntu runners
- Environment variables and GitHub context
- Simple CI steps and commands

## 📁 Workflow Structure

The main workflow is located at `.github/workflows/hello-world.yml` and includes:

### Workflow: "Hello GitHub Actions"
- **Trigger**: Runs on push to main branch, pull requests, and manual dispatch
- **Runner**: Ubuntu latest
- **Job**: `hello-world`

### Steps:
1. **Checkout Repository** - Uses `actions/checkout@v4`
2. **Say Hello** - Prints "Hello, GitHub Actions!"
3. **Show Environment Info** - Displays GitHub context variables:
   - Runner OS
   - GitHub Event type
   - Repository name
   - Branch name
   - Workflow initiator
4. **Show Current Date** - Displays the current date and time

## 🎯 Learning Objectives

After exploring this repository, you'll understand:

- ✅ How to create GitHub Actions workflows
- ✅ Basic YAML syntax for workflows
- ✅ Different trigger events
- ✅ Job and step structure
- ✅ Using GitHub context variables
- ✅ Viewing workflow execution logs
- ✅ Understanding CI/CD concepts

## 🔧 How to Use

1. **View the Workflow**: Check `.github/workflows/hello-world.yml`
2. **See it in Action**: Go to the "Actions" tab to view workflow runs
3. **Trigger Manually**: Use the "Run workflow" button in the Actions tab
4. **Make Changes**: Edit files and push to see the workflow trigger automatically

## 📚 Next Steps

To expand your GitHub Actions knowledge:

- Add more complex CI steps (testing, building, deploying)
- Explore different actions from the GitHub Marketplace
- Set up matrix builds for multiple environments
- Add conditional steps and job dependencies
- Implement secrets and environment-specific configurations

## 🌟 Status

[![Hello GitHub Actions](https://github.com/barath-k/github-actions-learning/actions/workflows/hello-world.yml/badge.svg)](https://github.com/barath-k/github-actions-learning/actions/workflows/hello-world.yml)

---

**Happy Learning! 🎉**
