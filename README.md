# ChAMP devOps assignment

## Description

Provide a brief description of your project here.

## Prerequisites

Make sure you have the following tools installed before running the project:

- Docker
- Docker compose

## Getting Started

Follow these steps to set up and run the project locally:

1. Clone the repository:

```
git clone https://github.com/champ11111/career-track-devops.git
```

2. Navigate to the project directory:

```
cd career-track-devops
```

3. Start the Docker containers using Docker Compose:

```
docker compose up
```

5. The project should now be up and running locally. Access it in your browser at:

- User Service: http://localhost:3000
- Product Service: http://localhost:3001

## Configuration

You can configure the project by modifying the environment variables in the `docker-compose.yml` file.

## Cleanup

To stop and remove the Docker containers, run the following command:

```
docker compose down
```

This will stop and remove the containers, but the data volumes (e.g., MySQL data, MongoDB data) will be preserved. If you want to remove the volumes as well, use the --volumes flag:

```
docker compose down --volumes
```
