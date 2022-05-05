# GUIDA GENERALE DOCKER

Ogni servizio è suddiviso per branch. Tuttavia quasi tutti i servizi hanno come punto di riferimento la network dedicata. Per modificarla basta andare nel .env del branch di riferimento e il gioco è fatto.
Di seguito il comando per creare la network che ho utilizzato.

## CREAZIONE NETWORK DEDICATA PER I SERVIZI

```
docker network create -d bridge --subnet=172.21.0.0/16 --gateway=172.21.0.1 db_bridge
```

