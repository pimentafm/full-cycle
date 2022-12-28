build-image:
	docker build -t fernandompimenta/node-fullcycle:latest -f Dockerfile.prod .

run-container:
	docker run --rm --name node -d -p 3000:3000 fernandompimenta/node-fullcycle:latest
