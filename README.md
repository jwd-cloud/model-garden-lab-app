# Model Garden API Playground

This repo contains code to be used in labs where students complete a simple
application that uses two partner APIs to return LLM responses.

To set up and run the application:

1. Open Cloud Shell
2. Set up the application
   ```bash
   git clone
   cd model-garden-lab-app
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   export GOOGLE_CLOUD_PROJECT=$(gcloud config get-value project)
   export GOOGLE_CLOUD_REGION="us-central1"
   ```
3. Run the application
   ```bash
   streamlit run mg_apis.py
   ```
4. Open the Cloud Shell preview window and try the application
