# AUY1104-CICLO-DE-VIDA-DEL-SOFTWARE-II

![SDLC](https://github.com/miguelh612/AUY1104-CICLO-DE-VIDA-DEL-SOFTWARE-II/blob/main/sdlc.png)

## Pipeline CI/CD

### 1. Build and Test

Realiza la configuración inicial, instala las dependecias y realiza pruebas de manera automática para validar la aplicación.

### 2. ECR Build and Push

Construye la imagen Docker, le asigna un tag y la sube al repositorio en ECR.

### 3. ECS Deploy

Implementa la actualización en un rolling update, se activa cuando se detecta una imagen con un hash nuevo, la implementa en ECS.

### .env    

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_SESSION_TOKEN
- AWS_ACCOUNT_ID
- AWS_REGION
- ECR_REPOSITORY
- ECS_CLUSTER
- ECS_SERVICE
- ECS_TASK_FAMILY
- ECS_CONTAINER_NAME
