# Overlap between cloud engineering and AI systems engineering

⚙️ Draft version — content under review and subject to updates.

> NOTE: This is a work-in-progress overview of the overlap between cloud engineering and AI systems engineering. Next step: cross-reference each item with current skills / experience to highlight gaps and learning priorities.

## Core technical overlap

- Designing and operating distributed systems and microservices for model-serving APIs, data services, and orchestration layers.
- Using major cloud providers (AWS, Azure, GCP) to provision compute, storage, networking, and managed services used by AI workloads.
- Applying infrastructure-as-code (Terraform, CloudFormation, ARM, etc.) to build reproducible environments for training, evaluation, and production inference.
- Managing containers and orchestration (Docker, Kubernetes, serverless) for scalable, resilient deployment of model services and data pipelines.
- Implementing CI/CD pipelines to automate building, testing, and deploying services, extended to include model artifacts and data validation.

## Data, storage, and pipelines

- Designing data lakes/warehouses and storage strategies for large training and inference datasets (object storage, databases, streaming).
- Building and maintaining data pipelines (batch/streaming) that feed both traditional applications and ML feature stores or model inputs.
- Securing data at rest and in transit, including access control, encryption, and compliance for sensitive training and production data.

## Scalability, reliability, and performance

- Capacity planning and autoscaling for variable workloads, including model training jobs and highly spiky inference traffic.
- Designing for high availability, fault tolerance, and disaster recovery for AI-powered services, as for other cloud-native systems.
- Performance optimization at the infrastructure level (instance types, GPU/CPU mix, networking, caching) for latency- and throughput-sensitive AI services.

## Observability, operations, and security

- Setting up logging, metrics, tracing, and alerting for services, extended to track model-serving performance, resource usage, and pipeline health.
- Operational incident response and SRE-style practices (SLIs/SLOs, runbooks) for AI systems in production.
- Applying cloud security engineering principles (IAM, network segmentation, secrets management) to AI runtimes, notebooks, and pipelines.

## Platform and tooling integration

- Integrating managed AI/ML services (e.g., SageMaker, Azure ML, Vertex AI) into existing cloud environments and application architectures.
- Enabling collaboration by providing shared compute, storage, and tooling environments for data scientists and ML engineers.
- Cost management and optimization for large-scale compute and storage, especially for GPU-heavy training and inference workloads.
