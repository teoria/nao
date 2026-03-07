.PHONY: build up down restart logs shell run install clean

build:
	docker compose build

up:
	docker compose up -d

down:
	docker compose down

restart:
	docker compose restart

logs:
	docker compose logs -f

shell:
	docker compose exec agent /bin/bash

run:
	uv run nao run project

env:
	set -a; source project/.env; set +a

install:
	uv sync

clean:
	docker compose down --rmi local --volumes
