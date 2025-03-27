# SciCat dev setup using docker compose

This repository contains a minimal setup to run SciCat in a development environment using docker compose.

## Usage

Clone the repository with all submodules:

```bash
git clone --recurse-submodules git@github.com:semohr/scicat_dev_docker.git
```

### Start frontend and backend in watch mode

```bash
docker compose -f docker-compose.dev.yml up
```

