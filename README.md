# Grafana Stack Lab

Tere! Ma olen **Ott Tammik** ja see on minu Grafana observability labor. Panin kokku terve monitoring stack'i Dockeris, et õppida, kuidas logisid ja trace'e analüüsida.

## Mis on sees?
- **Grafana** - dashboard, kus kõike näeb
- **Loki** - logide server (nagu Elasticsearch, aga lihtsam)
- **Tempo** - trace'ide server (näeb päringute teid läbi rakenduste)
- **HotROD** - demo rakendus, mis genereerib trace'e
- **Log-generator** - genereerib pidevalt testlogisid

## Kuidas käivitada?
```bash
git clone git@github.com:tammikott/grafana-stack-lab.git
cd grafana-stack-lab
docker-compose up -d
