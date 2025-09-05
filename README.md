# pycodex

Simple FastAPI API.

## Development

Install dependencies:

```bash
pip install -r requirements.txt
```

Run locally:

```bash
uvicorn main:app --reload
```

## Deployment

This project is configured for deployment on Vercel using `vercel.json`, which routes all requests to `main.py`.
