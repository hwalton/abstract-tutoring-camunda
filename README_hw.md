# Fetch Upstream
    $ git fetch upstream
    $ git checkout main
    $ git merge upstream/main
    $ git push origin main
# Start docker container
    $ docker compose up -d
(dont use lightweight docker-compose-core.yaml)

# Close docker container

## Keep persistent data
    $ docker compose down
## Delete persistent data (reset engine)
    $ docker compose down -v
## If elasticsearch is causing problems, run:
    $ sudo chown -R 1000:1000 ./data/elastic
    $ chmod 777 ./data/elastic   ??
