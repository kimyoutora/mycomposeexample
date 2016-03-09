# Docker Compose Tutorial

[Docker Compose Getting Started](https://docs.docker.com/compose/gettingstarted/)

```bash
# building the web
docker build -t compose-tutorial-web .

# Spinning up the stack
docker-compose up

# Running one-off commands
docker-compose run web env

# stopping the services
docker-compose stop

# Viewing the web site on a mac
docker-machine ip MACHINE_VM
open http://MACHINE_VM_IP:5000
```
