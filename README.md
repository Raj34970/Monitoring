## About this playbook
This playbook installs the following monitoring agents
    - Promtail
    - Loki
    - Prometheus
    - Thanos
    - node-exporter
    - alloy

## Usage
```bash
    ansible-playbook -i inventory.ini main.yml -t install_all
```
