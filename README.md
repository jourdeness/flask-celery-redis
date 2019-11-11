# flask-celery-redis
Example of using Flask with Celery and Redis

## Instructions
1. Must have docker installed (docker for desktop).
2. CD into the root of the project
3. Create a .env file with the following env variables. Place it in the root directory (same level as docker-compose.yaml).
   ```
   COMPOSE_PROJECT_NAME=flask_celery_redis
   PYTHONUNBUFFERED=true
   ```
4. Build the containers
   ```
   docker-compose up --build
   ```
## Sample Screenshot 
https://quantmill.s3.eu-west-2.amazonaws.com/github/flask-celery-redis.PNG
