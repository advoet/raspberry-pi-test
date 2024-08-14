See: https://fastapi.tiangolo.com/tutorial/first-steps/#check-it

# Instructions (local)

From the project directory, run

```bash
docker build -t hello-pi .
docker run -p 80:80 hello-pi
```

Navigate to `127.0.0.1:80`

# Instructions (pi)

1. Clone and follow the above instructions.

2. Access on the local connection - e.g. 192.168.0.10:80

For bonus points - run in detached mode
```bash
docker run -dp 80:80 hello-pi
```

To kill:
```bash
docker container ls
```
```bash
docker container stop [your_container_id]
```
