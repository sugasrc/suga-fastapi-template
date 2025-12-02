# <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" height="24"> FastAPI on Suga <img src="https://github.com/sugasrc.png" height="24">

Create and deploy your FastAPI apps to your Kubernetes cluster with Suga in minutes.

## Getting Started

### 1. Create your repository

Click **Use this template** to create your own repository.

### 2. Develop locally

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python main.py
```

Server runs on http://localhost:8000

API docs available at http://localhost:8000/docs

### 3. Push your changes

This triggers GitHub Actions to build and push your image to GitHub Container Registry.

### 4. Update Suga

In the Suga dashboard, update your service's **Image URI** to:

```
ghcr.io/YOUR_USERNAME/YOUR_REPO:latest
```

> **Note:** Ensure your GHCR package is public.
