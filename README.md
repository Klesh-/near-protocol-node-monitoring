# near-protocol-node-monitoring
A monitoring tool based on Grafana + Prometheus for Near Protocol Node

![Grafana dasboard](./screenshots/image1.png "Grafana dasboard image")

# Setup

### Follow this guides to install docker engine and docker compose:
- https://docs.docker.com/desktop/install/linux-install/
- https://docs.docker.com/compose/install/

### Copy .env.example to .env
```sh
cp .env.example .env
```

### Fill script parameters in .env file
- **GRAFANA_ADMIN_USER** - Grafana admin user name
- **GRAFANA_ADMIN_PASSWORD** - Grafana admin password name

### Start
```sh
./start.sh
```

### Stop
```sh
./stop.sh
```

### Setup alerts channel
- Got to Alerting > Notification channels > Add channel > Add desired channel

# Stake Wars: Episode III. Challenge 004
https://github.com/near/stakewars-iii/blob/main/challenges/004.md

