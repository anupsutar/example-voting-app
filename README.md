# Example Voting App

A simple distributed application running across multiple containers.

## Getting started

This solution uses Python, Node.js, .NET, with Redis for messaging and Postgres for storage.

# Vote
On push, build docker image, test the docker image using Trivy, push the docker image to Docker Hub (`anupsutar/examplevotingapp_vote`), and deploy the application to Kubernetes.

# Worker
On push, build docker image, test the docker image using Trivy, push the docker image to Docker Hub (`anupsutar/examplevotingapp_worker`), and deploy the application to Kubernetes.

# Result
On push, build docker image, test the docker image using Trivy, push the docker image to Docker Hub (`anupsutar/examplevotingapp_result`), and deploy the application to Kubernetes.
