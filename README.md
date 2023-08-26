# Example API
Mock de API

# postman_collection
Informações para usar o postman e fazer as requisições

# Dockerfile
Para subir a api no docker e testar
```
Docker build -t example-api .
Docker run -dp 5000:5000 -w /app -v $(cwd_path):/app example-api 
```

