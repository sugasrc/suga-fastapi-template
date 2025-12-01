# <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" height="24"> FastAPI Template

Modern async Python API with automatic OpenAPI docs, type validation, and high performance.

## Local Development

Install dependencies:
```bash
pip install -r requirements.txt
```

Start the server:
```bash
python main.py
```

Server runs on http://localhost:8000

API docs available at http://localhost:8000/docs

## File Structure

```
├── main.py             # FastAPI app and routes
├── requirements.txt    # Python dependencies
└── Dockerfile          # Container build
```

---

## <img src="https://github.com/sugasrc.png" height="20"> Deploying with Suga

1. Click **Use this template** to create your own repository

2. Push changes - GitHub Actions builds and pushes to GHCR automatically

3. In the Suga dashboard, update the **Image URI** for your service:
   ```
   ghcr.io/YOUR_USERNAME/YOUR_REPO:latest
   ```

4. Ensure your GHCR package is public
