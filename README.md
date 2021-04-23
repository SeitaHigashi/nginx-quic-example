# NGINX QUIC Example
Example of NGINX QUIC server with [sepi/nginx-quic-preview](https://hub.docker.com/repository/docker/sepi/nginx-quic-preview).

## How to use
Create a self-signed certificate and place it in the conf folder.
```bash
git clone https://github.com/SeitaHigashi/nginx-quic-example
docker-compose up -d
```

Access to ```https://localhost``` with a browser that supports HTTP/3.