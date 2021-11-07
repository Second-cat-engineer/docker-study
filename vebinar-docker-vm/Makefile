run:
	docker run -d -p 80:4200 --env-file .env --rm --name logsapp logsapp:env
stop:
	docker stop logsapp

up:
	docker run -d -p 3000:4200 -v logs:/app/data --rm --name logsapp logsapp:volumes