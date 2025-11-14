.PHONY: prepare up down clean

prepare:
	mkdir -p data/node1/data data/node2/data
	chown -R 1000:1000 data

up: prepare
	docker compose up -d

down:
	docker compose down
