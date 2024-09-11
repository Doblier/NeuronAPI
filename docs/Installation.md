# Installation Guide

Follow these steps to get **NeuronAPI** up and running.

## Prerequisites:
- **Python 3.8+** installed
- **Docker** and **Docker Compose** installed
- Basic knowledge of FastAPI, Docker, and Kafka

## Steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/doblier/NeuronAPI.git
   cd NeuronAPI
   ```

2. **Create a virtual environment**:
   ```bash
   python3 -m venv env
   source env/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up Docker containers**:
   Run the following command to spin up Kafka, Postgres, and the core services:
   ```bash
   docker-compose up
   ```

5. **Run the application**:
   Use the CLI to set up your project and start the FastAPI app.
   ```bash
   python cli.py setup
   python cli.py up
   ```

That's it! Your NeuronAPI environment is now up and running.
