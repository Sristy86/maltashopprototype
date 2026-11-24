# MaltaShop Microservices Prototype

FastAPI + PostgreSQL order-service publishing OrderPlaced events over RabbitMQ to notification-service with idempotency and correlation_id tracing.

## Run
cp .env.example .env
docker compose up --build -d
