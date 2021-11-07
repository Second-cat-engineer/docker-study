ifndef ENV
	ENV = dev
endif

up:
	docker-compose up -d --build
	docker-compose exec php composer install
	cp .build/config/$(ENV)/.env .env
down:
	docker-compose down