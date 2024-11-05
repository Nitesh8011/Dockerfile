# Elastic Zero Count Index Cleanup

This Docker image deletes indices with zero document count in an Elasticsearch instance.

## Overview

The repository contains the necessary files to create a Docker image that identifies and deletes Elasticsearch indices with zero documents.

### Files Included

- **Dockerfile**: Defines the environment and dependencies for the Docker container.
- **dummy_index.py**: (Purpose here if needed, e.g., for testing or creating dummy indices)
- **main.py**: The main script to identify and delete Elasticsearch indices with zero documents.
- **requirement.txt**: Lists required Python libraries for the project.

## Usage

1. **Pull the Docker image** from Docker Hub:

   ```bash
   docker pull nitesh8011/github:elastic_zero_count
