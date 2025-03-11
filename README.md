# CICD-MCP

A simple containerized web application using Nginx.

## Quick Start

To run this application locally:

1. Clone the repository:
```bash
git clone https://github.com/akugelblitz/cicd-mcp.git
cd cicd-mcp
```

2. Build the Docker image:
```bash
docker build -t cicd-mcp .
```

3. Run the container:
```bash
docker run -d --name cicd-mcp-app -p 8080:80 cicd-mcp
```

## Accessing the Application

Once running, you can access the application at:
- http://localhost:8080

## Docker Configuration

The application uses:
- Base image: nginx:latest
- Exposed port: 80
- Default host port mapping: 8080->80

## Project Structure

```
.
├── Dockerfile      # Docker configuration file
└── README.md      # Project documentation
```

## License

This project is open source and available under the MIT License.