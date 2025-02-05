# Cypress GitHub Actions Integration

[![Youtube Thumbnail](how-to-intregrate-cypress-with-gh-actions-thumbnail.png)](https://youtu.be/yHZ_B1bkZfA?si=zRvU758n4VoZypEo)

This repository is a tutorial on how to integrate Cypress with GitHub Actions for automated end-to-end testing.



## About
Cypress is a popular end-to-end testing framework, and GitHub Actions is a CI/CD platform that allows you to automate workflows directly within your GitHub repository. Integrating the two ensures your tests run manually or automatically on each commit, pull request, or any configured event.

## Key Configuration
The most important configuration for this integration can be found in the following file:

```
cypress-gh-actions-example/.github/workflows/main.yml
```

This file contains the YAML definition of the GitHub Actions workflow, including:
- Events that trigger the workflow.
- Cypress test execution steps.
- Browser matrix testing setup.
- Report generation and artifact uploads.

Happy testing!
