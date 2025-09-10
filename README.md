# DevOps Immersion – Alura

[![Build Status](https://img.shields.io/github/actions/workflow/status/rodrigodabreu/imersao_devops_alura/ci.yml?branch=main)](https://github.com/rodrigodabreu/imersao_devops_alura/actions)  
[![Docker](https://img.shields.io/badge/Docker-ready-blue?logo=docker)](https://www.docker.com/)  
![Python](https://img.shields.io/badge/Python-3.9+-yellow?logo=python)  
[![License](https://img.shields.io/github/license/rodrigodabreu/imersao_devops_alura)](./LICENSE)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/yourprofile)

> Repository containing code, data, and configuration files used during the *DevOps Immersion* course hosted by Alura.

## Overview

This repository consolidates my hands-on experience acquired during Alura's DevOps Immersion course. It includes Docker-based development environments, service orchestration through Docker Compose, and a sample application using Python and SQLite.

I created this project to showcase my evolving skills in DevOps practices — a journey that reflects my commitment to continuous learning in infrastructure as code, containerization, and deployment automation.

## Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Learning Objectives](#learning-objectives)  
- [Future Enhancements](#future-enhancements)  
- [About Me](#about-me)  
- [Contact](#contact)

## Features

- Dockerized application deployment  
- Simple Python web API interacting with a SQLite database  
- Service orchestration using Docker Compose  
- Sample database and ORM models demonstrating backend logic  
- Workflow definitions in `.github/workflows` (CI/CD basics)

## Technologies Used

| Technology          | Purpose                                   |
|---------------------|-------------------------------------------|
| **Python**          | Core development language                 |
| **Docker**          | Containerization of services              |
| **Docker Compose**  | Multi-container orchestration             |
| **SQLite**          | Lightweight file-based database           |
| **GitHub Actions**  | CI/CD pipeline basics                     |
| **ORM (e.g., SQLAlchemy)** | Database modeling (if applicable) |

## Getting Started

### Prerequisites

Ensure you have the following tools installed:

- [Docker](https://www.docker.com/get-started) (Docker Engine & Docker CLI)  
- [Docker Compose](https://docs.docker.com/compose/) (may be included in Docker Desktop)  
- [Git](https://git-scm.com/) (optional, for cloning the repo)

### Installation

```bash
git clone https://github.com/rodrigodabreu/imersao_devops_alura.git
cd imersao_devops_alura
```

### Usage
Clone the repository and run the project locally:
```bash
# Clone the repository
git clone https://github.com/rodrigodabreu/imersao_devops_alura.git

# Navigate to the project folder
cd imersao_devops_alura

# Build Docker image
docker build -t my-app .

# Run with Docker
docker run -p 8080:8080 my-app

```

Acess the API or Application end-points at http://localhost:8080

To tear down the environment:
```bash
docker-compose down
```

### Project Structure
```bash
├── .github/workflows/      # CI/CD workflow definitions
├── Dockerfile              # Image build configuration
├── docker-compose.yml      # Service orchestration setup
├── app.py                  # Main application logic (API)
├── database.py             # DB connection setup
├── models.py               # ORM model definitions
├── schemas.py              # Data validation schemas
├── escola.db               # Preloaded SQLite database
├── requirements.txt        # Python dependencies
└── README_ALURA.md         # Original Portuguese documentation
```


### Learning Objectives
* Learn how to containerize applications using Docker
* Orchestrate multi-service setups with Docker Compose
* Implement a backend API in Python with database integration
* Understand ORM modeling and schema validation
* Explore the basics of CI/CD with GitHub Actions
* Familiarize myself with lightweight database (SQLite) setups

### Future Enhancements
* Migrate from SQLite to PostgreSQL or MySQL for scalability
* Add unit and integration tests with coverage reports
* Enhance CI/CD workflows for automated testing and deployment
* Implement logging and monitoring tools (e.g., ELK stack, Prometheus)
* Containerize frontend components (e.g., React) for full-stack deployment
* Explore IaC tools like Terraform for infrastructure provisioning

### About Me
I am a Brazilian software engineer with experience in Java, Spring Boot, SQL Server, MongoDB, and DevOps practices.
My current career goal is to secure an international position as a Java Back-end Developer, where I can apply my technical expertise, contribute to distributed teams, and continue growing in modern software engineering practices.

### Contact
* [LinkedIn](https://www.linkedin.com/in/rodabreu/)
* [GitHub](https://github.com/rodrigodabreu/)
* [Instagram](https://www.instagram.com/rodabreu/?hl=en)


