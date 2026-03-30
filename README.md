# 🚀 Observabilidade do Sistema

Este projeto configura um ambiente de **observabilidade** usando **Docker**, **Prometheus** e **Grafana**.  
Monitora métricas do sistema e envia alertas configurados.

---

## 📂 Estrutura do projeto

- `docker-compose.yml` - Orquestração dos containers  
- `prometheus.yml` - Configuração do Prometheus  
- `alerts.yml` - Configurações de alertas  
- `grafana/` - Dashboards e configurações do Grafana  

---

## ⚙️ Como usar

1. Certifique-se de ter **Docker** e **Docker Compose** instalados.  
2. Na raiz do projeto, execute:

```bash
docker-compose up -d
Acesse os serviços:
Prometheus: http://localhost:9090
Grafana: http://localhost:3000
Para acompanhar os logs em tempo real:
docker-compose logs -f

💡 Dica: para logs de um container específico:

docker-compose logs -f prometheus
docker-compose logs -f grafana
Para parar o ambiente:
docker-compose down
🛠 Tecnologias
Docker – Contêinerização
Prometheus – Coleta de métricas
Grafana – Visualização e dashboards
Alertmanager – Alertas configuráveis
👨‍💻 Desenvolvedor
Elizeu Rodrigues
GitHub: Elizeu25
