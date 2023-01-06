# rootfs 
```sh
podman export $(podman create docker.io/library/debian:latest) > debian.tar
zstd debian.tar 
```
