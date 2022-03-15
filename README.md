# README


```bash
docker ps --format "table {{.ID}}\t{{.Name}}\t{{.Networks}}"
```

```bash
docker run -d --hostname my-rabbit --name some-rabbit rabbitmq:3-management
```