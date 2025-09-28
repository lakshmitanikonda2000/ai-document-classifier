# AI-Powered Document Classifier

NLP service that classifies large, unstructured documents and reduces manual review time.

## Highlights
- Implemented token lookup with Tries and optimized string-matching to achieve ~95% classification accuracy.
- Asynchronous pipeline using AWS SQS + Lambda to process large batch jobs; reduced manual review by ~60%.
- Containerized with Docker and deployed via Kubernetes; includes health checks and auto-scaling.

## Tech Stack
Python · AWS Lambda · SQS · Docker · Kubernetes · Terraform · PyTorch / Transformers

## Getting Started
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pytest
