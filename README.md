# CounterFit Docker Container

A docker container with CounterFit installed.

When you run this container, you need to map port 5000 inside the container to a port on your local machine. You can then access CounterFit at localhost using that port.

For example:

```sh
docker run -p 5001:5000 jimbobbennett/counterfit:latest
```

Then open `http://localhost:5001`.

This container has been deployed to DockerHub: 
