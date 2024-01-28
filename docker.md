### stop and remove all containers (instead of prune)

```shellscript
docker ps -aq | xargs docker stop | xargs docker rm
```
### stop docker desktop
```shellscript
ps ax|grep -i docker|egrep -iv 'grep|com.docker.vmnetd'|awk '{print $1}'|xargs kill
```

