# Sailing Quote Agent

A Theoriq agent that provides sailing-themed quotes based on ETH price movements.

## Description

This agent analyzes Ethereum price trends and responds with sailing-themed quotes that metaphorically reflect the market conditions. It's built using the Theoriq Agent SDK and integrates with the Theoriq protocol.

## Setup

1. Clone this repository
2. Copy `.env.example` to `.env` and fill in your Theoriq private key
3. Install dependencies with Poetry:
   ```bash
   poetry install
   ```

## Running Locally

```bash
poetry run python main.py
```

The agent will be available at `http://localhost:8000`.

## Deployment

This agent is designed to be deployed on DigitalOcean's App Platform. See the Theoriq documentation for detailed deployment instructions.

## Environment Variables

- `AGENT_PRIVATE_KEY`: Your Theoriq agent private key
- `THEORIQ_URI`: Theoriq backend URI
- `FLASK_PORT`: Port for the Flask application (default: 8000)

## License

MIT