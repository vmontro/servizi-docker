# GUIDA ALL'UTILIZZO DI WORDPRESS CON DOCKER

## N.B.

Il servizio di wordpress si trova nella network creata db_bridge. Si raccomanda di creare la network db_bridge e di alzare il servizio mysql e phpmyadmin presenti nell'elenco dei branch.
Una volta creato il servizio creare il DB wordpress e modificare il file di configurazione .env.

## Guida per alzare il servizio di **filerun**:

- Creare una cartella con un nome a piacimento (preferibilmente "filerun")
- Entrare nella cartella creata
- Creare una cartella chiamata **FR-files** (in questa cartella verranno memorizzati i file caricati su filerun)
- Scaricare il file **docker-compose.yml** e relativo **file di configurazione .env**
- Digitare il seguente comando:

```
docker-compose up -d
```