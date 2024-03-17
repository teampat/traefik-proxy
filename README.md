# Setup Traefik Proxy

1. Create docker network traefik-proxy

```bash
docker network create traefik-proxy
```

2. Create basicauth.users file to auth dashboard
   You can generate your password with an [online htpasswd generator](https://www.web2generators.com/apache-tools/htpasswd-generator) or htpasswd command:

```bash
htpasswd -nbB <username> <password>
```
