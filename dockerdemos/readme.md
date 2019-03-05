# Demo

## Run with compose

```bash
docker-compose up -d
```

## Run with Swarm

```bash
docker stack deploy --compose-file docker-compose.yml demo
```

## Run with k8s

```bash
docker stack deploy --orchestrator kubernetes --compose-file docker-compose.yml demo
```
