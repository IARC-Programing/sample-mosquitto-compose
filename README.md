# Mosquitto Docker Compose

Sample Eclipse Mosquitto Docker Compose 

Equipvalent to docker run command

```
$ docker run -it -p 1884:1884 -p 9001:9001 -v mosquitto.conf:/mosquitto/config/mosquitto.conf -v /mosquitto/data -v /mosquitto/log eclipse-mosquitto
```
