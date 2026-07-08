# Hello Captain Docker Project

This project demonstrates a simple Docker image built using Alpine Linux that prints **"Hello, Captain!"** and then exits.

## 🔗 Project Repository

**GitHub:** [Project Captain](https://github.com/Saeed-280/project-captain/tree/main)

## Prerequisites

- Docker installed on your system

## Project Structure

```text
.
├── Dockerfile
└── README.md
```

## Dockerfile

```dockerfile
FROM alpine:latest
CMD ["echo", "Hello, Captain!"]
```

## Build the Docker Image

Run the following command from the project root directory:

```bash
docker build -t hello-captain .
```

## Run the Docker Container

```bash
docker run --name cont1 hello-captain
```

## Expected Output

```text
Hello, Captain!
```

The container will print the message and exit successfully.

https://roadmap.sh/projects/basic-dockerfile
