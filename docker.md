## stop and remove all containers (instead of prune)

```shellscript
docker ps -aq | xargs docker stop | xargs docker rm
```


