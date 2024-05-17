# Document Question and Answering RAG Application

Welcome to the Document Question and Answering RAG Application! This project leverages cutting-edge technologies to provide robust question-answering capabilities using a retrieval-augmented generation (RAG) model. By integrating multiple advanced tools and platforms, this application ensures efficient, scalable, and automated deployment processes.

## Project Overview

This repository contains the source code and deployment scripts for the Document Question and Answering RAG Application. The application is designed to retrieve and generate accurate answers from a corpus of documents, leveraging the power of machine learning and modern cloud infrastructure.

## Key Features

- **Advanced Question-Answering**: Utilizes state-of-the-art RAG models from Huggingface to deliver precise answers from a given document set.
- **Scalable Deployment**: Employs AWS AppRunner and AWS Elastic Container Registry (ECR) for scalable and reliable deployment.
- **Efficient Retrieval**: Uses FAISS for fast document retrieval to enhance the performance of the RAG model.
- **Streamlined Development**: Integrated with Docker and GitHub Actions for seamless continuous integration, continuous delivery, and continuous deployment (CI/CD).
- **Interactive Interface**: Built with Streamlit for an intuitive and user-friendly interface.
- **Experiment Tracking**: Utilizes LangSmith for tracking experiments and managing model performance.

## Technologies Used

### Cloud and Containerization
- **AWS AppRunner**: For deploying and managing the application in a serverless manner.
- **AWS ECR**: To store and manage Docker container images.
- **Docker**: Ensures consistency across different development and deployment environments.

### Machine Learning and Retrieval
- **Langchain**: For constructing flexible and powerful language model pipelines.
- **FAISS**: Fast, efficient similarity search and clustering of dense vectors.
- **Huggingface**: Implements state-of-the-art RAG models for question answering.

### CI/CD
- **GitHub Actions**: Automates the workflow from code commit to deployment, using environment variables for secure configuration.

### User Interface
- **Streamlit**: Provides a simple and interactive web interface for end-users to interact with the application.

### Experimentation and Management
- **LangSmith**: Helps in managing, tracking, and experimenting with different model versions and configurations.

## Project Structure

Here's a brief overview of the project structure:

