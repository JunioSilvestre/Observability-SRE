# 01-prometheus — Prometheus & Coleta de Métricas

Instalação, configuração de scraping, exporters (Node, Blackbox), PromQL e Alertmanager.

## 📂 Subáreas
- [`instalacao/`](./instalacao) — **Stack:** `prometheus.yml, systemd, docker` — Implantação resiliente do servidor de métricas Prometheus e configuração de retenção.
- [`targets-exporters/`](./targets-exporters) — **Stack:** `node_exporter, blackbox_exporter, custom exporters` — Instrumentação de servidores Linux, banco de dados e endpoints de rede.
- [`metricas-promql/`](./metricas-promql) — **Stack:** `PromQL, rate, irate, histogram_quantile, sum` — Consultas analíticas avançadas para cálculo de saturação, tráfego e latência.
- [`alertmanager/`](./alertmanager) — **Stack:** `alertmanager.yml, routing, receivers, inhibition` — Roteamento inteligente de alertas para Slack, PagerDuty, Discord e webhooks.

## 📌 Guia de Execução & Padrões
- Todas as implementações desta pasta seguem os padrões de produção estabelecidos para Observability-SRE.
- Consulte os READMEs de cada subárea para detalhes sobre ferramentas e boas práticas.
