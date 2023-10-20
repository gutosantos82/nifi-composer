# nifi-composer - working for Nifi and Anony
Build NoHarm Integration

## 1. Install Docker compose 
Based on https://docs.docker.com/compose/install/linux/

For Ubuntu:
``` sudo apt-get install docker-compose ```

## 2. Clone the repository
``` git clone https://github.com/noharm-ai/nifi-composer/ ```

## 3. Update the environment variables (noharm.env)

## 4. Compose Up

``` docker login ```

set user and password

``` cd nifi-composer ```

``` docker-compose up -d```

Wait until the containers are ready...

``` docker logout```


### Reference commands for Docker Compose: https://docs.docker.com/engine/reference/commandline/compose_up/
