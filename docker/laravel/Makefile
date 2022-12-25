build-image:
	docker build -t fernandompimenta/laravel-fullcycle:latest -f Dockerfile.prod .

run-container:
	docker run --rm --name laravel -d -p 8000:8000 fernandompimenta/laravel-fullcycle:latest
