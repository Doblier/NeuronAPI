# Usage Guide

NeuronAPI allows you to quickly generate microservices and manage them using the integrated CLI.

## Creating a Microservice

To create a new microservice, run the following CLI command:
```bash
python cli.py add-microservice "Create a microservice for user authentication using JWT and Postgres"
```


This command will:

- Generate a microservice scaffold in the services/ folder.
- Set up routes, models, and database connections automatically.
- Add Kafka and Postgres integration.

## Modifying a Microservice

After generating a microservice, you can modify it via prompt-driven code generation. Use the CLI:
```bash
Copy code
python cli.py modify-microservice "Add password hashing to the authentication service"
This will update the code, and you can see changes in real-time.
```

## Accessing the APIs
Once the services are running, you can interact with the API endpoints via the browser or curl commands:
```bash
Copy code
curl http://localhost:8000/api/auth
```