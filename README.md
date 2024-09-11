# NeuronAPI
NeuronAPI is a lightweight, AI-driven orchestration framework designed to simplify the creation and management of microservices. Built on top of FastAPI and Docker, it enables developers to spin up microservices, integrate LLMs, and orchestrate complex systems with minimal effort.

## Features
- Async-first design for scalability.
- Native integration with FastAPI and Docker.
- AI-driven code generation and service orchestration.
- Support for local and cloud-hosted LLMs.
- Ready-to-use Kafka and Postgres setup via Docker Compose.

## Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/doblier/NeuronAPI.git
   ```

2. Set up the project:
   ```bash
    cd NeuronAPI
    python cli.py setup
    docker-compose up
   ```

3. Interact with the generated APIs:
   ```bash
    curl http://localhost:8000/api/example   
   ```

# Contributing

Contributions are welcome! Please read our [Code of Conduct]() and [Contributing Guide]() for more information.