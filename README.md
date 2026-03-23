#### Introduction of project-hub
Hello! Thank you for visiting. 

This repository is a central hub to my projects, providing an overview of what I have worked on and what I am currently exploring. 

#### Project Overview

- Data Engineering Foundations 
    - [data_engineering_projects](https://github.com/leanya/data_engineering_projects)
        - A collection of foundational data engineering projects inspired by the Udacity Data Engineering Nanodegree, including work with relational databases, NoSQL systems, and Airflow pipelines

- Machine Learning and Experimentation
    - [mlflow](https://github.com/leanya/mlflow)
        - A machine learning experimentation project that tracks runs, tunes parameters, compares models, and manages model version
        - Focus: MLflow

- News Headlines Data Engineering Series
    - This series started out as an batch processing app to scrape, clean, and store news headlines daily for visualisation using Docker Compose on EC2. It extended to include  AWS infrastructure provisioning and app health monitoring, followed by deployment using Kubernetes and Helm. A real-time streaming version of the app was also developed

    - [batch_processing_bbc](https://github.com/leanya/batch_processing_bbc)
        - Core batch processing pipeline
        - Focus: PostgreSQL, Streamlit, Docker Compose, CI/CD, Text Mining
    - [batch_processing_bbc_infra](https://github.com/leanya/batch_processing_bbc_infra) 
        - Infrastructure provisioning and monitoring
        - Focus: Terraform, Prometheus, Grafana, Docker Compose, CI/CD
    - [batch_processing_bbc_kubernetes](https://github.com/leanya/batch_processing_bbc_kubernetes)
        - Kubernetes and Helm Deployment
        - Focus: Container Orchestration, Kubernetes, Helm, CI/CD
        - [Accompanying notes on medium](https://medium.com/@LeanNotes/lessons-learned-from-deploying-kubernetes-on-ec2-using-helm-and-github-actions-57606c11d4a8?postPublishedType=initial)
    - [real_time_rss_feeds](https://github.com/leanya/real_time_rss_feeds)
        - Real-time streaming version
        - Focus: Kafka, MongoDB, MongoDB Kafka Sink Connector, Flask

- Retrival-Augmented Generation (RAG) chatbot
    - [RAG chatbot](https://github.com/leanya/study_rag)
        - This project implements a Retrieval-Augmented Generation (RAG) chatbot to support the study of data structures topics. By grounding responses with external documents, RAG reduces hallucination and generates answers that are more relevant and aligned with the topics.
        - Focus: ElasticSearch, Google AI API, HuggingFace, FastAPI, Streamlit, Docker Compose
        - [Accompanying notes on medium](https://medium.com/@LeanNotes/building-a-rag-chatbot-with-fastapi-and-streamlit-dd5ab9bd7e8e)


- Low-Rank Adaptation (LoRA) chatbot
    - [LoRA chatbot](https://github.com/leanya/lora_translation)
        - This project demonstrates LoRA fined-tuned MarianMT model for English to French translation. Adapters are added to the key and value projections in self-attention and cross-attention layers.
        - Focus: HuggingFace, FastAPI, Gradio

- Invoice AI Automation Workflow
    - [Invoice AI workflow](https://github.com/leanya/invoice-ai-workflow)
    - This project implements an AI automation workflow that extracts, validates, stores invoice data from PDF documents using LLM prompt engineering, with a human-in-the-loop review process for uncertain cases.
    - Focus: Google AI API, FastAPI, LLM Prompt Engineering, PostgreSQL, Docker Compose


 