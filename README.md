# OpenVPN UDP Proxy

This project is a simple OpenVPN UDP proxy using Nginx and Docker. It is designed to forward traffic to a specified target host.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository
2. Navigate to the project directory
3. Run `docker compose up -d` to start the services
4. To stop the services, run `docker compose down`

## Configuration

The configuration for the proxy is done through environment variables in the `docker-compose.yml` file:

- `LISTEN_PORT`: The port on which the proxy listens for incoming connections.
- `TARGET_HOST`: The target host to which the proxy forwards the traffic.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
