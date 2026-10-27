# 02-grafana — Grafana & Visualização de Dados

Construção de dashboards operacionais e executivos, alerting nativo e provisionamento como código.

## 📂 Subáreas
- [`datasources/`](./datasources) — **Stack:** `Prometheus, Loki, Tempo, OpenSearch datasources` — Conexão e autenticação com múltiplos repositórios de telemetria.
- [`dashboards/`](./dashboards) — **Stack:** `Dashboard as Code, JSON models, variáveis dinâmicas` — Visualização clara dos 4 Golden Signals (Latência, Tráfego, Erros e Saturação).
- [`alertas/`](./alertas) — **Stack:** `Grafana Unified Alerting, notification policies` — Definição de regras de alerta visuais e limites baseados em consultas.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Observability-SRE.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
