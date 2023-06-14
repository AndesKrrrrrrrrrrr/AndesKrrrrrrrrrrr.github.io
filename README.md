# Hello World 😻




## Podman and `testcontainers`

```
# Configure "docker" to use 'testcontainers'
DOCKER_HOST=unix://${XDG_RUNTIME_DIR}/podman/podman.sock
TESTCONTAINERS_RYUK_DISABLED=true
systemctl --user start podman.socket
```


