# PostgreSQL & Redis Development Docker Compose

This repository contains a Docker Compose configuration for setting up a development environment with PostgreSQL and Redis. It's designed to provide a quick and easy way for development.


## 🚀 Features

- PostgreSQL
- Redis
- Environment variable configuration
- Resource management for containers
- Easy use


## 🔧 Usage

1. Clone this repository:

```bash
docker network create your-network # default is 'devdev'
git clone https://github.com/hunter-ji/postgres-redis-dev-docker-compose.git
cd postgres-redis-dev-docker-compose
```

2. Edit the `.env` file and set the values for your environment.

3. To start the services:

```bash
docker-compose up -d
```

To stop the services:

```bash
docker-compose down
```

To view logs:

```bash
docker-compose logs
```

