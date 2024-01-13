# Build it

In root:
`docker build -t api-test:111 . -f php/Dockerfile`

`docker build -t nginx-api:111 . -f nginx/Dockerfile`

# Run it

`docker-compose up --remove-orphans --build --pull force`