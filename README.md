# Pipeline CI/CD eBank Microservices

This repository contains the CI/CD pipeline configuration for the eBank microservices production environment.

## Table of Contents

- [Introduction](#introduction)
- [Architecture](#architecture)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project provides a comprehensive CI/CD pipeline for deploying eBank microservices to a production environment. It ensures automated testing, building, and deployment of the microservices.

## Architecture

The pipeline follows a multi-stage approach:
1. **Source Code Management**: Code is managed in GitHub.
2. **Continuous Integration**: Automated tests are run on each commit.
3. **Continuous Deployment**: Successful builds are deployed to the production environment.

## Technologies

- **GitHub Actions**: For CI/CD workflows.
- **Docker**: Containerization of microservices.
- **Kubernetes**: Orchestration of microservices.
- **Helm**: Kubernetes package management.
- **Terraform**: Infrastructure as Code (IaC).

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/LuciferMorningstar33/pipeline-ci-cd-ebank-microservices-prod.git
    ```
2. Navigate to the project directory:
    ```sh
    cd pipeline-ci-cd-ebank-microservices-prod
    ```


## Usage

- Push changes to the repository to trigger the CI/CD pipeline.
- Monitor the pipeline status on GitHub Actions.
- Check the deployment status on your Kubernetes cluster.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.