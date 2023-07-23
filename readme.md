# Docker compose for creating server for monitoring DB amd HA using Grafana 


### to do : 
- Create config for HA which automatically connect to DB 
- Nginx page which shows all services 
- still have problems with the connection grafana and prometeus 

## cread one docker compose 
- Home Assistace
- Grafana
- Prometeus 
- Postgres 
- Admin panel for Postgres 
- Pihole 

## Second step Python: 
- create python program for write data about system to DB 
- create program for backup for DB and using AWS S3 


STEP 1 : 

use python program for write your password 

STEP 2 : 

RUN docker compose with env 
`docker-compose --env-file /path/to/my/custom.env up -d`