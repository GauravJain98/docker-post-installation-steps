# Docker Post Installation Steps

```bash 
sudo groupadd docker
sudo usermod -aG docker $USER
```
## Log out and then Log In

``` bash
newgrp docker 
```

## Test
docker run hello-world
