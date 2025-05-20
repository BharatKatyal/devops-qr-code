docker build -t qr-code-api .
docker run -p 8000:8000 --env-file .env qr-code-api