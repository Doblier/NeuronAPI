# LLM Integration

NeuronAPI allows developers to integrate **Large Language Models (LLMs)** to assist with the dynamic generation and modification of microservices.

## Using Cloud-hosted LLMs:
- If you want to use a cloud-hosted LLM, you'll need an API key for the provider.
- In your `.env` file, add your API key like this:
  ```
  LLM_API_KEY=your-api-key-here
  ```

## Running LLM Locally:
- If you have GPU-enabled hardware, you can run the LLM locally by downloading the necessary open-source models like **LLaMA**.

## Creating Microservices with LLM:
Use the following prompt to generate a new microservice:
```bash
python cli.py add-microservice "Create a service for real-time notifications with Kafka"
```

The LLM will generate the code for the requested microservice, including the routes, Kafka integration, and other required services.