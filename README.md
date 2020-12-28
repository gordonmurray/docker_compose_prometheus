# Prometheus, Alertmanager, Grafana and node-exporter

Bare minimum set up for experimenting with Prometheus

First, create a network with:

> docker network create my-network --subnet 172.24.24.0/24        

Then, run the containers with:

> docker-compose -f "docker-compose.yml" up -d --build 

Finally, navigate to :

> http://localhost:9090