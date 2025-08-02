# redmine

<p align="center">
  <img width="944" height="584" alt="msedge_x4JR5QBRsy" src="https://github.com/user-attachments/assets/b06a5f23-338b-4d6f-9b56-449b50a95416" />
</p>

## Production Deployment

Follow the instructions below to start and stop the production-ready Redmine container.

> **Warning:** Stopping with the `-v` flag will delete the container’s volumes and all stored data. Use with extreme caution.

Start container:

```bash
docker-compose -f docker-compose.prod.yml up -d
````

Stop container (preserve volumes):

```bash
docker-compose -f docker-compose.prod.yml down
```

Or stop container and remove volumes:

```bash
docker-compose -f docker-compose.prod.yml down -v
```
