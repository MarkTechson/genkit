# Chatbot

This is a simple chatbot. You can pick which model to use.

Prerequisite

- Google Cloud project with Vertex AI API enabled (https://console.cloud.google.com/apis/api/aiplatform.googleapis.com)
- gcloud CLI installed (https://cloud.google.com/sdk/docs/install-sdk)
- to use Llama 3.1 405b enable it in the Vertex AI [Model Garden](https://console.cloud.google.com/vertex-ai/publishers/meta/model-garden/llama3-405b-instruct-maas)

The sample is using Vertex AI, so you'll need to auth (you can skip this if running on IDX)

```bash
gcloud auth login
gcloud auth application-default login --project YOUR_PROJECT
```

Install deps and run the chatbot app

```bash
npm run setup
npm start
```

Point your browser to http://localhost:4200/

Inspect runs in http://localhost:4000/
