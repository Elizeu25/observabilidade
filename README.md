# Observabilidade do Sistema

Este projeto configura um ambiente de **observabilidade** usando **Docker**, **Prometheus** e **Grafana**.

## Estrutura do projeto

- `docker-compose.yml` - Orquestração dos containers.
- `prometheus.yml` - Configuração do Prometheus.
- `alerts.yml` - Configurações de alertas.
- `grafana/` - Dashboards e configurações do Grafana (se houver).

## Como usar

1. Certifique-se de ter o **Docker** e **Docker Compose** instalados.
2. Na raiz do projeto, execute:
   ```bash
   docker-compose up -d

Acesse:
Prometheus: http://localhost:9090
Grafana: http://localhost:3000
Desenvolvedor: Elizeu Rodrigues



