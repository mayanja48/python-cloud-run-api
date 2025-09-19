# Python Flask API on Google Cloud Run

A simple "Hello World" API built with the Flask framework and deployed on Google Cloud Run using the `gcloud` CLI.

## How to Deploy

1. Clone this repository.
2. Run the following command:
```bash
gcloud run deploy python-api-service \
  --source . \
  --platform=managed \
  --region=us-central1 \
  --allow-unauthenticated
