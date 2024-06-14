# Fetch Upstream
```azure
$ git fetch upstream
$ git checkout main
$ git merge upstream/main
$ git push origin main
```
# Start docker container
```azure
$ docker compose up -d
```
(dont use lightweight docker-compose-core.yaml)

# Close docker container

## Keep persistent data
```azure
$ docker compose down
```
## Delete persistent data (reset engine)
```azure
$ docker compose down -v
```

