## Run Tidis in one command using docker-compose

1. Clone tidis-docker-compose repo

```
~ git clone https://github.com/yongman/tidis-docker-compose.git
```

2. Run

```
~ cd tidis-docker-compose/

~ docker-compose up -d
Creating network "docker_default" with the default driver
Creating docker_pd_1 ... done
Creating docker_tikv_1 ... done
Creating docker_tidis_1 ... done
```

3. Stop and delete

```
~ docker-compose down
```

**This compose file is just use one pd and one tikv instance for test, not for production**
