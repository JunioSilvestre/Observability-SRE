# 08-laboratorios — Laboratórios Práticos de Observabilidade

Ambientes de teste com Docker Compose para subir a stack completa.

## 📂 Subáreas
- [`stack-lgtm/`](./stack-lgtm) — **Stack:** `Loki, Grafana, Tempo, Mimir (LGTM)` — Ambiente local completo com Docker Compose para experimentação.
- [`node-exporter-dashboards/`](./node-exporter-dashboards) — **Stack:** `Linux Host Monitoring` — Painel corporativo pronto para monitorar CPU, RAM, Disco e Rede.
- [`synthetic-monitoring/`](./synthetic-monitoring) — **Stack:** `Blackbox Exporter + Prometheus` — Sondagem contínua de status HTTP/HTTPS, certificados TLS e portas de rede.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Observability-SRE.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
