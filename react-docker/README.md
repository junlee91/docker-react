- Build Image
```
docker build -f Dockerfile.dev .
```

- Run with volume
```
docker run -p 3000:3000 -v usr/app/node_modules -v $(pwd):/usr/app ${CONTAINER_ID}
```

- Use Docker compose
```
docker-compose up
```
