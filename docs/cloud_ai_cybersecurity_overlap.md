# Overlap between cybersecurity engineering and AI systems engineering

⚙️ Draft version — content under review and subject to updates.

> NOTE: This is a work-in-progress overview of the overlap between cybersecurity engineering and AI systems engineering. Next step: cross-reference each item with current skills / experience to highlight gaps and learning priorities.

## Data security & privacy

- Implementing PII detection, anonymization, and data masking in training datasets, feature stores, and data pipelines.
- Establishing secure data lineage, audit trails, and access logging for compliance with GDPR, HIPAA, and other regulations.
- Deploying differential privacy techniques and federated learning architectures to protect data during model training.

## Model security

- Protecting against model theft through API rate limiting, watermarking, and fingerprinting of model outputs.
- Mitigating model poisoning attacks, adversarial examples, and backdoor vulnerabilities in training data and inference.
- Implementing secure model versioning, rollback mechanisms, and integrity verification for production models.

## Infrastructure security

- Securing multi-tenant GPU/TPU environments with workload isolation, resource quotas, and runtime sandboxing.
- Managing secrets, API keys, and credentials for model serving endpoints, data pipelines, and MLOps tooling.
- Applying container security best practices (pod security policies, image scanning, runtime protection) to model serving infrastructure.

## Supply chain security

- Scanning ML framework dependencies, training libraries, and infrastructure tools for known vulnerabilities.
- Maintaining Software Bill of Materials (SBOMs) for AI stacks and implementing artifact signing for models and containers.
- Establishing trusted model registries with access controls, provenance tracking, and reproducibility verification.

## Observability & incident response

- Monitoring model serving endpoints for security events, unusual inference patterns, and access anomalies.
- Implementing anomaly detection for training data integrity, model drift indicating potential compromise, and inference attacks.
- Developing incident response playbooks for compromised training data, model tampering, and production inference security breaches.
