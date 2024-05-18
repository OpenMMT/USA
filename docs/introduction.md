# Introduction to OpenMMT

Welcome to the OpenMMT project! This document serves as an introduction to the project, outlining its purpose, goals, and key components. Whether you are a contributor, user, or simply interested in learning more about macroeconomic modeling, this guide will provide you with the foundational knowledge needed to understand and engage with OpenMMT.

## Project Overview

OpenMMT is an open-source initiative aimed at developing a comprehensive macroeconomic model of the United States based on the principles of Modern Monetary Theory (MMT). Our goal is to democratize economics by making sophisticated economic modeling accessible to everyone. We aim to provide tools and models that help explain the relationships between federal taxes, government spending, inflation, and various economic actors.

## Vision and Mission

### Vision
To create a transparent and accessible platform for macroeconomic modeling that empowers individuals, educators, policymakers, and researchers to understand and influence economic policy and outcomes.

### Mission
- **Transparency**: Make economic modeling transparent and understandable to a broad audience.
- **Accessibility**: Provide tools and resources that are freely available and easy to use.
- **Collaboration**: Foster a collaborative environment where diverse contributions are valued and encouraged.
- **Education**: Serve as a valuable educational resource for students, educators, and anyone interested in macroeconomics.

## Key Objectives

1. **Accurate Representation**: Develop models that accurately reflect the complexities of the U.S. economy, including interactions between public and private sectors, inflation, and fiscal policies.
2. **Dynamic System Modeling**: Implement dynamic system models to capture both short-term fluctuations and long-term trends in the economy.
3. **Collaborative Development**: Encourage contributions from economists, data scientists, programmers, and enthusiasts to build a robust and comprehensive model.
4. **Educational Resource**: Provide tools and resources that can be used for teaching and learning about macroeconomics.
5. **Standardization**: Create standardized models that can be used for testing and developing economic theories outside the academic realm.

## Components of OpenMMT

### Taxonomy Standards
A set of standards and definitions that ensure consistency and clarity in the economic models and data used in the project. These standards help maintain uniformity in data representation and interpretation.

### Data Models
Detailed representations of the economic data used in the models. This includes defining the structure, sources, and relationships between different data points. Proper data modeling ensures the accuracy and reliability of the simulations.

### Algorithms
The mathematical and computational methods used to analyze economic data and simulate economic scenarios. These algorithms are the core of our modeling efforts, providing the means to interpret data and predict outcomes.

### Simulations
Models that allow users to explore and test different economic scenarios and policies. Simulations provide insights into potential outcomes and effects of various economic actions, helping users understand complex economic dynamics.

## Project Folder Structure

The following is the folder structure of the OpenMMT project, along with descriptions of each directory and its contents:

```
OpenMMT/ <br>
├── README.md <br>
├── CONTRIBUTING.md <br>
├── CODE_OF_CONDUCT.md <br>
├── LICENSE <br>
├── docs/ <br>
│   ├── introduction.md <br>
│   ├── taxonomy_standards.md <br>
│   ├── data_models.md <br>
│   ├── algorithms.md <br>
│   ├── simulations.md <br>
│   └── ... <br>
├── models/ <br>
│   ├── data_models/ <br>
│   │   └── ... (data model files) <br>
│   ├── algorithms/ <br>
│   │   └── ... (algorithm scripts) <br>
│   └── simulations/ <br>
│       └── ... (simulation scripts and models) <br>
├── data/ <br>
│   ├── raw/ <br>
│   │   └── ... (raw data files) <br>
│   ├── processed/ <br>
│   │   └── ... (processed data files) <br>
│   └── external/ <br>
│       └── ... (external data files) <br>
├── src/ <br>
│   ├── data_processing/ <br>
│   │   └── ... (data processing scripts) <br>
│   ├── modeling/ <br>
│   │   └── ... (modeling scripts) <br>
│   └── simulation/ <br>
│       └── ... (simulation scripts) <br>
├── tests/ <br>
│   ├── data_processing/ <br>
│   │   └── ... (tests for data processing scripts) <br>
│   ├── modeling/ <br>
│   │   └── ... (tests for modeling scripts)
│   └── simulation/ <br>
│       └── ... (tests for simulation scripts) <br>
├── .github/ <br>
│   ├── ISSUE_TEMPLATE.md <br>
│   ├── PULL_REQUEST_TEMPLATE.md <br>
│   └── workflows/ <br>
│       └── ci.yml (GitHub Actions workflow for CI/CD) <br>
└── scripts/ <br>
    ├── setup/ <br>
    │   └── ... (setup scripts for initializing the project) <br>
    └── utils/ <br>
        └── ... (utility scripts) <br>
```

### Directory Descriptions

- **README.md**: A high-level overview of the project, including the purpose, vision, and how to get started.
- **CONTRIBUTING.md**: Guidelines for contributing to the project, including reporting issues, proposing changes, and submitting pull requests.
- **CODE_OF_CONDUCT.md**: The code of conduct for participants, ensuring a respectful and inclusive community.
- **LICENSE**: The project's license file, specifying the terms under which the project can be used and contributed to.

- **docs/**: Contains all documentation files.
  - **introduction.md**: An introduction to the project, providing detailed information about its purpose, vision, objectives, and components.
  - **taxonomy_standards.md**: Documentation on taxonomy standards used in the project.
  - **data_models.md**: Documentation on data models.
  - **algorithms.md**: Documentation on algorithms used.
  - **simulations.md**: Documentation on simulation methodologies.

- **models/**: Contains the actual models used in the project.
  - **data_models/**: Directory for data model files.
  - **algorithms/**: Directory for algorithm scripts.
  - **simulations/**: Directory for simulation scripts and models.

- **data/**: Stores all data files used in the project.
  - **raw/**: Directory for raw data files.
  - **processed/**: Directory for processed data files.
  - **external/**: Directory for data from external sources.

- **src/**: Source code for data processing, modeling, and simulation.
  - **data_processing/**: Scripts for data processing.
  - **modeling/**: Scripts related to modeling.
  - **simulation/**: Scripts related to simulation.

- **tests/**: Contains test files for different parts of the project.
  - **data_processing/**: Tests for data processing scripts.
  - **modeling/**: Tests for modeling scripts.
  - **simulation/**: Tests for simulation scripts.

- **.github/**: GitHub-specific files and workflows.
  - **ISSUE_TEMPLATE.md**: Template for GitHub issues.
  - **PULL_REQUEST_TEMPLATE.md**: Template for GitHub pull requests.
  - **workflows/**: Directory for GitHub Actions workflows.
    - **ci.yml**: Continuous integration configuration file.

- **scripts/**: Utility scripts and setup scripts.
  - **setup/**: Setup scripts for initializing the project.
  - **utils/**: Utility scripts that might be needed for various tasks.

## How to Get Involved

We welcome contributions from individuals with diverse backgrounds and expertise. Here’s how you can get involved:

### Reporting Issues
If you find a bug or have a feature request, please [open an issue](https://github.com/chevannanayakkara/OpenMMT/issues). Provide as much detail as possible, including steps to reproduce the problem, expected behavior, and screenshots if applicable.

### Proposing Changes
If you have an idea for a new feature or an improvement to the existing codebase, start by opening an issue to discuss your idea. This helps align your contributions with the project’s goals and avoid duplicating efforts.

### Contributing Code
Check out our [contribution guidelines](../CONTRIBUTING.md) for information on how to contribute code and documentation. Follow the steps outlined to fork the repository, make your changes, and submit a pull request.

### Collaborating on Documentation
Contributions to the project’s documentation are highly valued. If you find areas of the documentation that can be improved, feel free to make changes and submit a pull request. Clear and concise documentation helps everyone understand and use the project effectively.

## Getting Started

To get started, follow these steps:

1. **Clone the Repository**: Clone the OpenMMT repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/OpenMMT.git
   ```

2. **Set Up Your Environment**: Follow the setup instructions in the [README.md](../README.md) to configure your development environment.

3. **Explore the Documentation**: Read through the documentation in the `docs/` directory to familiarize yourself with the project’s components and standards.

4. **Start Contributing**: Look for open issues and tasks in the [issues](https://github.com/chevannanayakkara/OpenMMT/issues) section and start contributing!

## Conclusion

Thank you for your interest in OpenMMT! By working together, we can create powerful tools for understanding and influencing economic policy. We look forward to your contributions and collaboration.
