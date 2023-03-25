# DevOps-CI-CD-Pipeline-Project

This repository contains a Java-based project using Spring framework technologies to create a DevOps Continuous Integration and Continuous Deployment (CI/CD) pipeline.

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [Testing](#testing)
7. [CI/CD Pipeline](#cicd-pipeline)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

The DevOps-CI-CD-Pipeline-Project aims to provide a seamless CI/CD pipeline for Java applications developed using the Spring framework. By following best practices and utilizing various DevOps tools, this project simplifies and automates the development, testing, and deployment of Java applications.

## Prerequisites

Before you start, ensure that you have the following software installed on your system:

- Java JDK 8 or higher
- Maven 3.6.0 or higher
- Docker 19.03 or higher
- Git

## Installation

1. Clone the repository: git clone https://github.com/username/DevOps-CI-CD-Pipeline-Project.git

2. Navigate to the project directory: cd DevOps-CI-CD-Pipeline-Project

3. Build the project using Maven: mvn clean install


## Configuration

This project uses the following environment variables for configuration:

- `SPRING_PROFILES_ACTIVE`: Set the active Spring profile (e.g., `development`, `production`, `test`)
- `DATABASE_URL`: Set the connection URL for the database
- `DATABASE_USERNAME`: Set the username for the database
- `DATABASE_PASSWORD`: Set the password for the database

Make sure to set these variables accordingly in your environment or application configuration file.

## Usage

To run the application locally, execute the following command:

java -jar target/devops-ci-cd-pipeline-project-0.0.1-SNAPSHOT.jar

The application will be accessible at http://localhost:8080.

## Testing

To execute unit tests, run the following command:

mvn test


## CI/CD Pipeline

The project includes a CI/CD pipeline using the following tools:

- Git for version control
- Jenkins for continuous integration and deployment
- Docker for containerization
- Kubernetes for container orchestration

To set up and configure the CI/CD pipeline, follow the instructions in the `pipeline.md` file.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) to get started.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

# I'm Janaka Premathilaka,
📫 Feel free to reach out to me at janaka2@gmail.com , on [LinkedIn](https://www.linkedin.com/in/janakap/) or give me a call at +41 76 224 84 45. 💌 🚀


