### Docker

Remove the docker image 'zythologue-api-jn' even if running

```bash
docker rm -f demo-api
```

Build the docker image

```bash
docker build -t demo-api .
```

Run the docker image using a specified network

```bash
docker run --name demo-api --env-file .env -p 4242:4242 demo-api
```
# demo-api
# demo-api
