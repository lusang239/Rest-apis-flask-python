# CONTRIBUTING

## How to run the Dockerfile locally

```
docker run -dp 5050:5000 -w /app -v "$(pwd):/app" <IMAGE_NAME> sh -c "flask run --host 0.0.0.0"
```