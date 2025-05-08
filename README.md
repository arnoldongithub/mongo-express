# Mongo-Express Project

This is a simple setup for MongoDB and Mongo Express running on Kubernetes. It provides a web-based interface for managing your MongoDB database.

## Project Structure

- **mongo-deployment.yaml**: Kubernetes deployment configuration for MongoDB.
- **mongo-service.yaml**: Kubernetes service configuration for MongoDB.
- **mongo-express-deployment.yaml**: Kubernetes deployment configuration for Mongo Express.
- **mongo-express-service.yaml**: Kubernetes service configuration for Mongo Express.
- **mongo-secret.yaml**: Kubernetes secret configuration for MongoDB credentials.
- **mongo-express**: Configuration for the Mongo Express interface.
  
## Prerequisites

- Kubernetes cluster (Minikube, EKS, GKE, etc.)
- kubectl CLI
- Docker (for local testing)
