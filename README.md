# Example of Reverse Proxy with Docker
- webapp1 [httpd](https://hub.docker.com/_/httpd/)
- webapp2 [nginx](https://hub.docker.com/_/nginx/)
## Images



## Vhosts

Edit in `/etc/hosts`
```
127.0.0.1	webapp1.local
127.0.0.1	webapp2.local

## Run

```
docker-compose up -d
```

By Lucas Marques.
