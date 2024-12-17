# BWC :: GitHub Actions

This repository contains GitHub Actions YAML configuration files designed for automating tasks related to Hugo and deploying to Azure Static Web Apps. It includes actions for downloading and executing Hugo, as well as a custom deployment workflow for Azure Static Web Apps.

## Features

- **Hugo Workflow**: A GitHub Action for downloading and executing Hugo, streamlining the build and deployment process for Hugo-based sites.
- **Azure Static Web App Deployment**: A custom action for deploying Hugo-generated static sites to Azure Static Web Apps.

## Blog Series

Learn more about the improvements and optimizations made in these GitHub Actions through the following blog posts:

- [Hugo GitHub Action Improvements - Part One](https://blog.builtwithcaffeine.cloud/posts/hugo-github-action-improvements/)
- [Hugo GitHub Action Improvements - Part Two](https://blog.builtwithcaffeine.cloud/posts/hugo-github-action-improvements-part-two/)

## How to Use

1. Clone this repository or copy the individual YAML files into your own GitHub repository.
2. Adjust the workflows as necessary to fit your Hugo project and Azure deployment configurations.
3. Commit and push the changes to trigger the GitHub Actions workflows.

> [!NOTE]
> For 'azure-statuc-web-apps-template.yaml, Please update line 88 and 105 with your GitHub Secret value AZURE_STATIC_WEB_APPS_API_TOKEN*'

For detailed instructions on using the actions, refer to the blog posts linked above.

## Contributing

If you have suggestions or improvements for the GitHub Actions in this repository, feel free to fork and submit pull requests. Contributions are welcome!
