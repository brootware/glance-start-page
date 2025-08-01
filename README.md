# glance-start-page

This repository includes configuration files for a CI/CD pipeline and a web page layout.

## CI/CD Pipeline (`.gitea/workflows/cicd.yml`)
The CI/CD pipeline is set up using GitHub Actions. It ensures that YAML and JSON files are properly formatted whenever code changes are pushed to the main branch or when pull requests are created against it. The pipeline involves:
- Checking out the repository.
- Installing `yq` for parsing YAML files.
- Setting up Node.js v20 with `prettier`.
- Running checks to ensure that YAML files adhere to a consistent format.

## Configuration File (`glance.yml`)
This file is likely used as configuration for an application or service, possibly related to web page design. It defines the structure and behavior of the startpage, including:
- Page dimensions.
- Navigation settings.
- Widgets like search and bookmarks.
