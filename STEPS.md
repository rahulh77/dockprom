``` bash
# Spin up stack
docker-compose up -d

# apply config changes
docker restart <container-name>

docker-compose down -v
docker-compose down --remove-orphans -v

# In case of issues with volumes
docker volume ls
docker volume rm <name of volume>
```