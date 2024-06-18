# Nash
A small wrapper on top of nginx to add an UI for setting up a reverse proxy server.

## Commands
### Build the Docker image
```
docker build -t nash-proxy .
```

### Run the Docker container
```
docker run -d -p 80:80 nash-proxy
```