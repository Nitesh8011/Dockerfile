# RabbitMQ Cleanup

This Docker image is designed to perform cleanup tasks on a RabbitMQ instance.

## Overview

The repository contains the necessary files to create a Docker image that connects to RabbitMQ and performs maintenance or cleanup tasks.

### Files Included

- **Dockerfile**: Defines the environment and dependencies for the Docker container.
- **main.py**: The main script that connects to RabbitMQ and executes the cleanup tasks.
- **requirement.txt**: Lists required Python libraries for the project.

## Usage

1. **Pull the Docker image** from Docker Hub:

   ```bash
   docker pull nitesh8011/github:rabbitmq_cleanup
