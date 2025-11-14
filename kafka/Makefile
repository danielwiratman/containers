.PHONY: prepare up down clean

prepare:
	mkdir -p data/broker-1/data data/broker-1/metadata
	mkdir -p data/broker-2/data data/broker-2/metadata
	mkdir -p data/broker-3/data data/broker-3/metadata
	chown -R 1000:1000 data

up: prepare
	docker compose up -d

down:
	docker compose down
