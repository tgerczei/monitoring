# monitoring - containerized Prometheus and Grafana on HypriotOS

## usage
- docker volume create prometheus-tsdb
- docker volume create grafana-config
- docker volume create grafana-data
- sudo cp monitoring.service /lib/systemd/system/
- sudo systemctl daemon-reload
- sudo systemctl enable --now monitoring

### tested on HypriotOS v1.12.2 running on a Raspberry Pi 3B+
